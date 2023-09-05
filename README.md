# LessonEnd
Minutes left of current lesson
## FOR CZECH STUDENTS ONLY
Simple app that shows you on top right corner of your screen how many minutes left to end of your current lesson. Powered by Bakalari Api ver. 3, offering universal tool for all students. Color and size of minutes are customaziable.

## How To Use
1) Download and extract the RAR file
2) Then run the LessonEndConfigurator.exe and input all the fields
                        - dont include the "https://" for your school bakalari's URL!!
3) If all entered data are correct, a number or text "Volno" should appear in the corner, if not, run the LessonEnd.exe manually
4) Thats all, if you wish to get rid of that, open task manager (ctrl+alt+del) and kill the proccess by right clicking the app

Warning: I wanted to finish the app as quickly as possible, for this reason there might occur some unexpected bugs. Also, I thought no-one would like to steal yours Bakalari account so the password is stored as plain text!

I wanted to run the app on every system startup, but for some reason the WPF didnt work properly. Tried both methods, win registry and autorun folder but none of them helped, so you have to run the app each time manually.

## App Background
Once the app is up, your login credentials are used to download your timetable from Bakalari server, from which are being extracted the time all the lessons start and ends. Those numbers are saved and every 30 seconds is refreshed the number of minutes that left to end of current lesson or to start another one.

Showcase:

![example1](https://github.com/ondraxddd/LessonEnd/assets/92151973/f7343339-060d-4421-bb3f-e8feea66fed5)

![example2](https://github.com/ondraxddd/LessonEnd/assets/92151973/70e7b5dc-6b72-44c8-ae4d-4a801ef0cee7)
