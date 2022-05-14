```sql

CREATE TABLE programmers (
    name VARCHAR(255),
    github VARCHAR(255),
    age INT(3),
    country VARCHAR(255),
    languages VARCHAR(255),
    
    PRIMARY KEY(github)
    );
   
INSERT INTO programmers (name, github, age, country, languages)
VALUES (
    	"Isaque", 
	"github.com/isaquebraga",
        18, 
        "Brazil",
        "Python, Java, HTML, CSS, JavaScript and SQL"
	);
	
SELECT * 
FROM programmers
WHERE github = "github.com/isaquebraga";
```
