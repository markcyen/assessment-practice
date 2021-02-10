class HistoryClass

Attributes
----------
history_topic (string)
textbook (string)
textbook_read (boolean)
graded_essays (integer)
total_grades_added (integer)
other_readings (array)

Methods
-------
calculate_average_grade (calculates total_grades_added divided by graded_essays)
finished_reading (updates textbook_read to true)
change_textbook (updates textbook)
add_readings (adds another book or material to other_readings)
