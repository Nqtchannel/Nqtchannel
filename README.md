1 {
  "email" : " " ,
  "mật khẩu" : " " ,
  "adminOnly" : false ,
  "adminBot" : [
    
  ],
  "nickNameBot" : " " ,
  "tiền tố" : " # " ,
  "cơ sở dữ liệu" : {
    "type" : " local " ,
    "uriMongodb" : " " ,
    "Notes" : " type select * local * or * mongodb *, if select Mongodb, enter uri connect mongodb into uriMongodb phần, còn local sẽ tự lưu tệp json tại cơ sở dữ liệu thư mục "
  },
  "SERVER_UPTIME" : đúng ,
  "autoRefreshFbstate" : true ,
  "restartListenMqtt" : {
    "allow" : true ,
    "timeRestart" : 3600000 ,
    "logNoti" : true
  },
  "logEvents" : {
    "eventAndMessage" : true ,
    "read_receipt" : false ,
    "typ" : false ,
    "hiện diện" : sai
  },
  "logsbot" : true ,
  "OptionsApi" : {
    "forceLogin" : true ,
    "listeningEvents" : true ,
    "updatePresence" : true ,
    "listeningTyping" : true ,
    "logLevel" : " error " ,
    "selfListen" : false
  }
}
