#WaterView![image](https://github.com/LongMaoC/WaterView/blob/master/gif/waterview.gif)##TODO* ~~增加暂停，恢复功能~~* 增加根据进度显示的方法##属性| 属性                          | 说明                            || :---------------------------: |:-------------------------------:|| waterview_paint_color_first   |  第一只画笔颜色    || waterview_paint_color_second   | 第二只画笔颜色 || waterview_frame_color   | 边框画笔颜色 || waterview_frame_width   | 边框宽度，为0dp时不显示边框 || waterview_amplitude     | 振幅 ，参考值10到100之间        || waterview_up_velocity   | 上升速度上升速度，参考值5     || waterview_offset_increment_value   | 初项递增值，表示波浪的快慢 ，参考值0.4    || waterview_sleep_time   | 界面更新速度,单位毫秒，参考值100     |##监听监听结束```waterView.setListener(new WaterView.Listener() {          @Override          public void finish() {              Toast.makeText(MainActivity.this, "已经满了！！！", Toast.LENGTH_SHORT).show();          }      });```##有问题反馈在使用中有任何问题、意见或建议，欢迎反馈给我，可以用以下联系方式跟我交流* 邮件(chenxingyu1112@gmail.com)* QQ: 1209101049 
 
