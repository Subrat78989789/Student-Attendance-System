# Student-Attendance-System

# The aim and objectives of this project

The system should be able to detect students’ frontal faces in a classroom within 30% accuracy. Recognise student stored on a database of faces by matching them to images on a database with an accuracy within 30%.
The system should be able to match detected students faces cropped from an image to those on a database on the system. The system should be able to detect face and recognise when in range.
The algorithm implemented for the system’s functionality will achieve system accuracy within 20%.
The system designed will be user friendly with a Graphical User Interphase that will serve as an access to the functionalities of the system.

# Scope of the project.

The project encompasses a Face Recognition-based Attendance System developed using Python with Tkinter for the graphical user interface, OpenCV for face detection, and Pandas for data management. It offers functionalities such as user authentication, allowing password changes for security. Users can register new students by providing their IDs and names, with the system capturing their images for face recognition. Utilizing Haar Cascade Classifier for face detection and LBPH Face Recognizer for recognition, the system tracks attendance by recognizing registered students and records their details along with the date and time. Data is managed through CSV files, displayed using a Treeview widget in the GUI. The interface includes features like clear buttons, help documentation access, and displays the current date and time. With error handling mechanisms and support options provided, the system aims for efficiency, scalability, and ease of maintenance, offering a reliable solution for managing student attendance.

# User interface and Functionality 

![imgage alt](https://github.com/Subrat78989789/Student-Attendance-System/blob/main/Attendance/Student%20%20Attendance%20System%20by%20Subrat%20Gupta%201_19_2025%204_20_37%20PM.png) 

The user interface for the student attendance system is designed using Tkinter, a Python standard GUI toolkit. The interface provides functionalities for registering new students, taking attendance, and saving profiles. Here's a breakdown of the key components and functionalities:

•	Frames and Labels: 
The interface is divided into two frames, each containing labels and entry fields for entering student ID and name. There are also labels displaying messages and information about the system.

•	Buttons: 
Various buttons are provided for different actions, such as taking images, saving profiles, clearing fields, and taking attendance. These buttons trigger corresponding functions defined in the code.

•	Treeview Attendance Table:
A treeview widget is used to display the attendance records, including student ID, name, date, and time. Scrollbars are added for navigation in case of a large number of records.

•	Menu Bar: 
A menu bar is included at the top, offering options like changing the password, contacting support, and accessing about and user manual sections. These options provide additional functionalities and information to the user.

•	Functionality: The interface allows users to take images for registration, save student profiles, and take attendance based on face recognition. It also provides options for clearing fields and accessing help resources.

Overall, the user interface provides a user-friendly and intuitive way to interact with the student attendance system, facilitating tasks related to registration and attendance tracking.

Take Attendance:

•	Real-Time Recognition: The system utilizes real-time face recognition technology to identify students as they appear for attendance.

•	Record Logging: Upon recognition, the system logs attendance records containing relevant information such as student ID, name, date, and time. This recorded data provides a comprehensive overview of student attendance for administrative purposes.

Quit:

•	Program Termination: This functionality allows users to gracefully exit the application, ensuring all processes are terminated properly and system resources are freed. It provides a convenient way for users to end their session and close the application when needed.

Password Change:

•	Secure Access: Users are provided with the ability to change their password for accessing the system features. This functionality enhances security by allowing users to update their passwords periodically or in case of any security concerns, ensuring access control and user authentication.

Exit:

•	Application Closure: The 'Exit' functionality enables users to close the application, terminating all processes associated with it. It provides a straightforward way for users to end their interaction with the system, ensuring a smooth user experience.

Contact Information:

•	User Support: Users have access to contact information, allowing them to reach out for assistance or inquiries. This feature fosters user engagement and support by providing a channel for users to communicate with system administrators or support staff, addressing any issues or questions they may have.

About:

•	System Information: The 'About' functionality provides users with detailed information about the system, including its purpose, development team, version information, and any other relevant details. This helps users understand the system better and builds trust by providing transparency and clarity about its origins and objectives.

Clear:

•	Data Reset: The 'Clear' functionality allows users to reset input fields or clear displayed information on the user interface. It provides a convenient way to erase entered data or remove displayed content, facilitating a clean and organized interface.

Time and Date Display:

•	Real-Time Clock: The system displays the current time and date on the user interface, providing users with real-time information. This feature enhances user experience by keeping users informed about the current time and date within the application.


# References 

1.	OpenCV Library: https://opencv.org/
2.	Tkinter Documentation: https://docs.python.org/3/library/tkinter.html
3.	NumPy Documentation: https://numpy.org/doc/
4.	Pandas Documentation: https://pandas.pydata.org/docs/
5.	Python Imaging Library (PIL) Documentation: https://pillow.readthedocs.io/en/stable/
6.	datetime Module Documentation: https://docs.python.org/3/library/datetime.html
7.	csv Module Documentation: https://docs.python.org/3/library/csv.html
8.	Time Module Documentation: https://docs.python.org/3/library/time.html
9.	tkinter.simpledialog Module Documentation: https://docs.python.org/3/library/tkinter.simpledialog.html
10.	Face Recognition with OpenCV: https://realpython.com/face-recognition-with-python/
11.	IEEE Xplore Digital Library: https://ieeexplore.ieee.org/Xplore/home.jsp
12.	IEEE Computer Society Digital Library: https://www.computer.org/csdl
13.	IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI): https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=34
14.	IEEE Transactions on Image Processing: https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=83
15.	IEEE International Conference on Computer Vision (ICCV): https://ieeexplore.ieee.org/xpl/conhome/1000209/all-proceedings
16.	"Python for Data Analysis" by Wes McKinney, O'Reilly Media, 2017. ISBN: 978-1491957660
17.	"Mastering OpenCV 4 with Python" by Alberto Fernandez Villan, Packt Publishing, 2019. ISBN: 978-1789344912
18.	"Deep Learning" by Ian Goodfellow, Yoshua Bengio, and Aaron Courville, MIT Press, 2016. ISBN: 978-0262035613
19.	"Pattern Recognition and Machine Learning" by Christopher M. Bishop, Springer, 2006. ISBN: 978-0387310732
