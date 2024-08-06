# n3d
for reference

-- Create the Table
CREATE TABLE cases (
    id INTEGER PRIMARY KEY AUTOINCREMENT,
    case_id INTEGER NOT NULL,
    assignment TEXT NOT NULL,
    case_date DATE NOT NULL,
    nova_open BOOLEAN NOT NULL,
    workable BOOLEAN NOT NULL
);

-- Insert Data into the Table
INSERT INTO cases (case_id, assignment, case_date, nova_open, workable)
VALUES
(1, 'John Doe', '2024-01-15', 1, 1),
(2, 'Jane Smith', '2024-02-20', 0, 1),
(3, 'Alice Johnson', '2024-03-25', 1, 0),
(4, 'Bob Brown', '2024-04-10', 0, 0),
(5, 'Charlie Davis', '2024-05-05', 1, 1),
(6, 'Eve Clark', '2024-06-18', 1, 0),
(7, 'Frank White', '2024-07-22', 0, 1),
(8, 'Grace Lewis', '2024-08-30', 0, 0),
(9, 'Hank Hall', '2024-09-14', 1, 1),
(10, 'Ivy Green', '2024-10-05', 1, 0);
