<<TOC(3)>> 

== Page Summary ==
 * Maintainer status: developing

 * Page Editor: [[DinnerHowe| Howe]](xu zhihao), [[rocwang| Roc]](wangpeng)

 * License: TODO

== Overview ==
Features-what you can learn from this series tutorials.

== Preparation ==

== Bringup ==

=== Xbot Driver ===
In the package xbot_driver. This package is totally same as the kobuki_driver, excepts some different messages and publishers because of different sensors in robots, the framework and the most of them are familiar. Our goal is to try our best to make you use it as much as simple. What's more,serial port communication driver in python are provided in the folder xbot_driver.

=== Xbot Bringup ===

xbot_bringup contains the xbot_minimal.launch for launching all the driver program and xbotNodelet, vel_cmd_muxNodelet and so on. You can launch the xbot_bringup in command:

{{{
>roslaunch xbot_bringup xbot_minimal.launch
}}}

=== Other Aiding Softwares ===

xbot package is a much simple version of xbot bringup package which can drive the xbot moving and publish some necessary messages. The xbot driver subscribes the cmd_vel message to know how to move, but it has not enough functions to promote xbot move safely. You can launch xbot in command:

{{{
>roslaunch xbot xbot.launch
}}}
Just for your reference.
== Obstacle Avoidance ==
Waitting for implemention by CCK .

== navigation ==

 * [[Build a map with SLAM|SLAM Map Building with xbot]]
  How to generate a map using gmapping && hector
 * [[Xbot_navigation|Autonomous Navigation of a Known Map with xbot]]
  This tutorial describes how to use the xbot with a previously known map.

== Interactive ==
Waitting for implemention by WW .

== Applications ==
=== Talk and Recognition ===

 * [[baidu_speech| Baidu Speech AND Recognition]]

  This tutorial support user making a transform from Text To Speach(TTS) and from Speach to Text(Speech Recognition) by using Baidu's Speech API.

=== Youtu Face Recognition ===
Waitting for implemention by WP .

=== Looking forward to your contributions ===

== Simulation ==
Waitting for implemention by XZH .
== Development Corner ==

== Appendix ==
