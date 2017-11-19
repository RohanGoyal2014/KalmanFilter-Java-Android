# KalmanFilter-Java-Android
Kalman Filter for Indoor Positioning Systems Android

Kalman Filter for Android #Commit1

Java Android Version of kalman filter by slobdell

There seems to be a starvation problem between onSensorChanged thread and onLocationChanged thread.
Debug threads to look for problem or put breakpoints on above events.
I moved code from onSensorChanged to TriggerEventListener's OnTrigger. I made some chananges later.
Tested this On MOTOXPLAY.
TEXTVIEW seems to be freezed.
Will write more later after testing.
