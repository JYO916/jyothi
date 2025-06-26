tuple1 = (10,)    
tuple2 = ("Hello",)
print("Tuple 1:", tuple1)
print("Tuple 2:", tuple2)
print("Element of Tuple 1:", tuple1[0])
print("Element of Tuple 2:", tuple2[0])


roll_numbers = [101, 102, 103, 104, 105, 106, 107, 108, 109, 110,
                111, 112, 113, 114, 115]
student_names = ["joe", "sunny", "seetha", "sravya", "rakesh",
                 "ravinder", "deo", "kanna", "lira", "harry",
                 "Kevin", "Lilly", "Michael", "Nina", "Oscar"]
students_dict = dict(zip(roll_numbers, student_names))
students_set = set(student_names)
print("Initial Dictionary:", students_dict)
print("Initial Set:", students_set)
