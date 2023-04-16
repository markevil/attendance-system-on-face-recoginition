# face-recognition-based-attendance-system  

Do visit my blog for better explanations: https://machinelearningprojects.net/face-recognition-based-attendance-system/

![alt text](ss.png)
if not os.path.isdir('Attendance'):
    os.makedirs('Attendance')
if not os.path.isdir('static/faces'):
    os.makedirs('static/faces')
if f'Attendance-{datetoday()}.csv' not in os.listdir('Attendance'):
    with open(f'Attendance/Attendance-{datetoday()}.csv','w') as f:
        f.write('Name,Roll,Time')