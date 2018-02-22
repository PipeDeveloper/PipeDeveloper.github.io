<head>

<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.16/css/dataTables.bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/buttons/1.5.0/css/buttons.bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/select/1.2.4/css/select.dataTables.min.css">
<link href="https://gitcdn.github.io/bootstrap-toggle/2.2.2/css/bootstrap-toggle.min.css" rel="stylesheet">

</head>
<body>
<br/>
<div style="width: 95%; margin:0 auto;">
    <div id="updateNotificationBar"></div>
    <div id="notificationBar"></div>
    <div id="statusBar"></div>

    <div class="center">
        <h1>XMRigCC Dashboard</h1>
    </div>

    <form style="padding-bottom: 25px">
        <label><input id="hideOffline" type="checkbox" checked  data-toggle="toggle" data-size="mini" data-onstyle="success" data-offstyle="danger"/><span>Hide offline miners</span></label>
        <label><input id="showOfflineNotification" type="checkbox" checked data-toggle="toggle" data-size="mini" data-onstyle="success" data-offstyle="danger" /><span>Notify when miner went offline</span></label>
    </form>

    <table id="clientStatusList" class="table table-striped table-bordered" cellspacing="0" width="100%">
        <thead>
        <tr>
            <th class="center" width="2%"><i class="fa fa-square-o" id="selectAllTop"></i></th>
            <th>Miner Id</th>
            <th>Pool</th>
            <th>Status</th>
            <th>Algo</th>

            <th>Hashrate</th>
            <th>Hashrate 1m</th>
            <th>Hashrate 15m</th>

            <th>Hashrate Highest</th>
            <th>Hashes Total</th>
            <th>Avg. Time</th>

            <th>Shares Good</th>
            <th>Shares Total</th>
            <th>Last Update</th>
            <th>Edit</th>
        </tr>
        </thead>
        <tfoot>
        <tr>
            <th class="center" width="2%"><i class="fa fa-square-o" id="selectAllBottom"></i></th>
            <th class="left">Total:</th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
            <th></th>
        </tr>
        </tfoot>
    </table>

    <br/>
    <div class="modal fade" id="minerEditor" role="dialog">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal">&times;</button>
                    <h4 class="modal-title">Miner editor</h4>
                </div>
                <div class="modal-body">
                </div>
                <div class="modal-footer">
                    <button id="minerEditorSave" type="button" class="btn btn-success" data-dismiss="modal">Save</button>
                    <button type="button" class="btn btn-default" data-dismiss="modal">Close</button>
                </div>
            </div>

        </div>
    </div>

    <div class="modal fade" id="multiMinerEditor" role="dialog">
        <div class="modal-dialog modal-lg">
            <div class="modal-content">
                <div class="modal-header">
                    <button type="button" class="close" data-dismiss="modal">&times;</button>
                    <h4 class="modal-title">Multi miner editor</h4>
                </div>
                <div class="modal-body">
                    <div class="alert alert-danger fade in">
                        <strong>Warning!</strong> - If you don't know what you are doing, [Cancel].
                    </div>
                    <h5 class="modal-title">
                        This will search for <strong>"x"</strong> and replace with <strong>"y"</strong> in all selected miners config<br/><br/>
                        <div class="alert alert-info fade in">
                            <strong>If you accidentally pressed [Replace], no worries just PULL again all miner configs. Don't PUSH it!</strong>
                        </div>
                    </h5>
                    <div class='form-group'>
                        <label for='search'>Search for:</label>
                        <textarea class='form-control' rows='2' cols="1" id='search'></textarea>
                        <label for='replacement'>Replace with:</label>
                        <textarea class='form-control' rows='2' id='replacement'></textarea>
                    </div>
                </div>
                <div class="modal-footer">
                    <button id="multiMinerEditorReplace" type="button" class="btn btn-success" data-dismiss="modal">Replace</button>
                    <button type="button" class="btn btn-danger" data-dismiss="modal">Cancel</button>
                </div>
            </div>
        </div>
    </div>
</div>
</body>
