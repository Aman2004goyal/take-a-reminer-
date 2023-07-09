from plyer import notification
import time
if __name__ == '__main__':
  while True:
    notification.notify(
      title = "please take rest",
      message="rest le lijiye vrna rest in peace ho jaoge",
      app_icon= "E:\Pelfusion-Long-Shadow-Ios7-Reminder.512 (1).ico",
      timeout=10)
    time.sleep(20)
