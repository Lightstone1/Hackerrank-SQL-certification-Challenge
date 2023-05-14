# Hackerrank-SQL-certification-Challenge

SELECT
       s.roll_number,
       s.name,
       
       FROM
       student_information as s
       LEFT JOIN
       faculty_information as f
       on s.advisor=f.employee_ID
       WHERE
       (gender = 'M' AND Salary > 15000)
       OR
      (gender = 'F' AND Salary > 20000);
