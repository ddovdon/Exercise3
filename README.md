# Exercise3
Database query

2.1.

SELECT UserName 
  FROM [User]
  where (Email is null or Email = ' ') or (Phone is null or Phone = ' ')

2.2
SELECT UserName, Address 
  FROM [User]
  where UPPER(City) = 'FARGO'
