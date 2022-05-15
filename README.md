```sql
CREATE TABLE me (
    name      VARCHAR(255) NOT NULL,
    github    VARCHAR(255),
    age       INT(3) NOT NULL,
    country   VARCHAR(255),
    languages VARCHAR(255),
    
    PRIMARY KEY (github)
);
   
INSERT INTO me (name, github, age, country, languages)
VALUES (
    	"Isaque", 
	"github.com/isaquebraga",
        18, 
        "Brazil",
        "Python, Java, HTML, CSS, JavaScript and SQL"
);
	
SELECT * 
FROM me
WHERE github = "github.com/isaquebraga";
```
