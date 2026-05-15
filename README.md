# [CMPS3162] Test 2: Music Job Queue

| Attribute      | Details                                                    |
| -------------- | ---------------------------------------------------------- |
| Name           | [Jennessa Sierra](https://www.github.com/jennxsierra/)     |
| Email          | [2021153908@ub.edu.bz](mailto:2021153908@ub.edu.bz)        |
| Course Name    | Advanced Databases                                         |
| Course Code    | CMPS3162                                                   |
| Due Date       | May 14, 2026                                               |

## Youtube Video Demonstration

Link: https://youtu.be/KkpXy8a5EsY

## Database Setup

```markdown
CREATE role music_user WITH LOGIN PASSWORD 'music';
CREATE DATABASE music_jobs;
ALTER DATABASE music_jobs OWNER TO music_user;
```

### Running the SQL file

In the project directory and having `psql` logged into the database, run:

```markdown
\i music_jobs.sql
```
