# gstreamer_support_demo

Steps:

To Save videos: Create folder /mnt/av with write permissions
mkdir -p /mnt/av
chmod 777 -R /mnt/av

To Build:
git clone https://github.com/ndndemos/gstreamer_support_demo.git
cd gstreamer_support_demo
mkdir -p build
cd build
cmake ..
make


To Run:
./rtsp2webrtc_1_n
Please enter rtsp url
<Enter any valid rtsp url with H.264 encoding>

-> Keep waiting for minimum 3-4 mins, each file is configured for 90 secs
Files generated in path: /mnt/av, Examples as below
/mnt/av/testvideo-1__1887930741.mp4 -> Playing on Chrome
/mnt/av/testvideo-2__1358928742.mp4 -> Not Playing on Chrome
/mnt/av/testvideo-3__1125121133.mp4 -> Not Playing on Chrome
/mnt/av/testvideo-4__1673889000.mp4 -> Not Playing on Chrome