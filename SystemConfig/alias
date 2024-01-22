alias tgxmzh="adb root && adb remount && adb shell settings put secure user_setup_complete 1 && adb shell settings put global device_provisioned 1 && adb reboot && adb wait-for-device && sleep 10 && adb root && adb remount && adb shell pm disable com.xiaomi.account" 
alias kc="/bin/bash /home/xiongzhengyao/files_1t/useful_scripts_all/other_scripts/other_scripts/kill-camera.sh"
alias screen_display="/bin/bash ~/files_1t/screen_display.sh"
alias pressure_test="/bin/bash ~/files_1t/useful_scripts_all/install_apk.sh && adb push /home/xiongzhengyao/files_1t/houji /sdcard/MIUI/plans/sanity"
# adb shell kill -9 $(adb shell ps -A |grep camera|awk '{print $2}' | head -n 2)
# /home/xiongzhengyao/files_1t/useful_scripts_all/set_log_levels.sh
alias openlog="/bin/bash /home/xiongzhengyao/files_1t/useful_scripts_all/set_log_levels.sh"
alias bpsraw='adb shell find /data/vendor/camera/ -name "IMG_202*" > files.txt && xargs -a files.txt -I{} adb pull {} && xargs -a files.txt -I{} adb shell rm {} && rm files.txt'
alias houji_chi="source build/envsetup.sh && lunch miodm_houji_cn-userdebug && RECOMPILE_KERNEL=1 LTO=thin ./kernel_platform/build/android/prepare_vendor.sh"
alias clear_offlinelog="adb shell find /data/vendor/camera/offlinelog/ -type f > files.txt && xargs -a files.txt -I{} adb shell rm {} && rm files.txt"
alias clear_image="adb shell find /data/vendor/camera/ -name 'IMG_202*' > files.txt && xargs -a files.txt -I{} adb shell rm {} && rm files.txt"
alias vermeer_all="source build/envsetup.sh && lunch miodm_vermeer_cn-userdebug && RECOMPILE_KERNEL=1 LTO=thin ./kernel_platform/build/android/prepare_vendor.sh && cd vendor/qcom/proprietary/camx-ishtar && mma -j8 && cd ../camx-common-ishtar && mma -j8 && cd ../camx-api-ishtar && mma -j8 && cd ../chi-cdk-ishtar && mma -j8"

alias pull_offlinelog="/bin/bash /home/xiongzhengyao/files_1t/useful_scripts_all/pull_offline_log.sh"
