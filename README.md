     maven {
            //url "http://47.106.250.204:8866/RobotLibs"
            url "https://raw.githubusercontent.com/ximenGG/RobotLibs/master"
        }   
    implementation 'com.guoguang:idcard:1.0.0'//读卡器
    implementation 'com.gosuncn.aiui:aiui:1.0.0'//语音转文字
    implementation 'us.pinguo.svideo:svideo:1.0.0'//视频录制
    implementation 'com.gosuncn.serialport:serialport:1.0.0'//读串口
    implementation('com.gosuncn.speech:speech:1.0.0') {//文字转语音
        exclude group: 'com.android.support'
    }
    implementation('com.gosuncn.facelib:facelib:1.0.0') {//人脸抓拍
        exclude group: 'com.android.support'
    }
    implementation('com.gosuncn.logger:logger:1.0.0') {//日志输出
        exclude group: 'com.android.support'
    }
