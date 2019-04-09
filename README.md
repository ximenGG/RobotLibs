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
