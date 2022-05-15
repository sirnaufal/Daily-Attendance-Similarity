# Daily Attendance Similarity Model

Background
--- 
Every weekday employee from a company fill in daily attendance using google form. One of many field in google form that employee must fill is today work list. Now, there are certain employee or division whom HR division suspects always fill in same or similar today work list every time. Therefore, the company decided to find suspected employee or division by making machine learning model.

Model Goal
--- 
Create Machine Learning Model to flag every entry that have similar today work list to other entry from the same employee in daily attendance form.

Dataset
--- 
Dataset for this model comes from google sheet that filled by every employee using google form. Each row in the dataset represents each entry and each column in the dataset contains specific information from each entry.

Column Information:

    Timestamp: Day and time of absence
    Nama Lengkap Anda: Employee full name
    Divisi / Division: Employee Division
    Lokasi Absensi / Location of Attendance: Location of absence
    List Pekerjaan Hari Ini / Today Work List (08.30 - 12.00): Today Morning Work List
    List Pekerjaan Hari Ini / Today Work List (13.00 - 17.30): Today Afternoon Work List
    Rencana Pekerjaan Besok / Work Plan Next Day: Work list next day
    Kendala pekerjaan pada saat WFH / Problem during WFH: Whether there is a problem during WFH
    Kondisi saya saat ini / My current condition: Employee condition 
    monthyear:
    ddmonthyear:
    flag WFH / WFO:
    flag Problem WFH:
    flag Safe:
