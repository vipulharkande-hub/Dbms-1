REFERENCES s (roll_no),
    FOREIGN KEY (course_id)
        REFERENCES c (course_id)
);INSERT INTO department VALUES
(1, 'Computer Science'),
(2, 'Electronics');

INSERT INTO student VALUES
(101, 'Milisha', 'milisha@gmail.com', '123456789012', 1),
(102, 'Rahul', 'rahul@gmail.com', '987654321098', 2);

INSERT INTO course VALUES
(501, 'DBMS', 1),
(502, 'Circuits', 2);

INSERT INTO enrollment VALUES
(101, 501, 3, 'A');

INSERT INTO enrollment VALUES
(101, 502, 3, 'B');


SHOW TABLES;
DESCRIBE student;
SHOW CREATE TABLE enrollment;
SELECT * FROM enrollment;


SELECT * FROM department;
SELECT * FROM student;
SELECT * FROM course;
SELECT * FROM enrollment;


CREATE TABLE faculty (
    faculty_id INT PRIMARY KEY,
    faculty_name VARCHAR(50) NOT NULL,
    email VARCHAR(50) UNIQUE,
    phone_no VARCHAR(15) UNIQUE,
    dept_id INT,
    FOREIGN KEY (dept_id) REFERENCES department(dept_id)
);

INSERT INTO faculty VALUES
(201, 'Dr. Sharma', 'sharma@gmail.com', '9876543210', 1),
(202, 'Prof. Mehta', 'mehta@gmail.com', '9876543211', 2);

SELECT * FROM faculty;
