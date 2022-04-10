## Câu 1 :
Viết chương trình cài đặt phương pháp Bootstrap để xuất ra phân bố lấy mẫu và dải tin cậy của một thông số thống kê của một biến (đặc trưng) nào đó của dataset với:

• Biến (đặc trưng): do SV chọn từ dataset

• Thông số thống kê: giá trị trung bình (GTTB)

• Viết hàm có:•Input parameters: n (sample size), M (number of bootstrap samplings), x (confidence interval in %)

• Return values: phân bố lấy mẫu (bằng histogram) và dải tin cậy của GTTB của đặc trưng đã chọn

## Câu 2 :
Dựa trên cùng dataset với Câu 1, viết chương trình xuất ra và thuyết trình các thống kê mô tả quan trọng của các biến, các mối quan hệ giữa các biến đã có và biến tạo thêm (nếu có), quy luật tiềm ẩn có thể suy diễn từ dataset nhờ các công cụ trực quan hoá dữ liệu (ví dụ: distribution plot, heat/cluster map, linear model plot,…).

## Data Description
ID: A unique ID to identify a candidate

Salary: Annual CTC offered to the candidate (in INR)

Gender: Candidate's gender

DOB: Date of birth of the candidate

10percentage: Overall marks obtained in grade 10 examinations

10board: The school board whose curriculum the candidate followed in grade 10

12graduation: Year of graduation - senior year high school

12percentage: Overall marks obtained in grade 12 examinations

12board: The school board whose curriculum the candidate followed

CollegeID: Unique ID identifying the university/college which the candidate attended for her/his undergraduate

CollegeTier: Each college has been annotated as 1 or 2. The annotations have been computed from the average AMCAT scores obtained by the students in the college/university. Colleges with an average score above a threshold are tagged as 1 and others as 2.

Degree: Degree obtained/pursued by the candidate

Specialization: Specialization pursued by the candidate

CollegeGPA: Aggregate GPA at graduation

CollegeCityID: A unique ID to identify the city in which the college is located in.

CollegeCityTier: The tier of the city in which the college is located in. This is annotated based on the population of the cities.

CollegeState: Name of the state in which the college is located

GraduationYear: Year of graduation (Bachelor's degree)

English: Scores in AMCAT English section

Logical: Score in AMCAT Logical ability section

Quant: Score in AMCAT's Quantitative ability section

Domain: Scores in AMCAT's domain module

ComputerProgramming: Score in AMCAT's Computer programming section

ElectronicsAndSemicon: Score in AMCAT's Electronics & Semiconductor Engineering section

ComputerScience: Score in AMCAT's Computer Science section

MechanicalEngg: Score in AMCAT's Mechanical Engineering section

ElectricalEngg: Score in AMCAT's Electrical Engineering section

TelecomEngg: Score in AMCAT's Telecommunication Engineering section

CivilEngg: Score in AMCAT's Civil Engineering section

Conscientiousness: Scores in one of the sections of AMCAT's personality test

Agreeableness: Scores in one of the sections of AMCAT's personality test

Extraversion: Scores in one of the sections of AMCAT's personality test

Nueroticism: Scores in one of the sections of AMCAT's personality test

Openesstoexperience: Scores in one of the sections of AMCAT's personality test

Salary : salary