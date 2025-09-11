SELECT MAX(salary) AS third_highest
FROM employee
WHERE salary < (
    SELECT MAX(salary)
    FROM employee
    WHERE salary < (
        SELECT MAX(salary) 
        FROM employee
    )
);
