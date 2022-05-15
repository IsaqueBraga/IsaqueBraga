```sql
CREATE TABLE me (
    name      VARCHAR(255) NOT NULL,
    github    VARCHAR(255),
    age       INT(3) NOT NULL,
    country   VARCHAR(255),
    languages VARCHAR(255),
    doing     VARCHAR(255) CHECK (doing = "Studying" OR doing = "Procrastinating"),
    
    PRIMARY KEY(github)
);
   
INSERT INTO me (name, github, age, country, languages, doing)
VALUES (
    	"Isaque", 
	"github.com/isaquebraga",
        18, 
        "Brazil",
        "Python, Java, HTML, CSS, JavaScript and SQL",
	"Procrastinating"
);
	
SELECT * 
FROM me
WHERE github = "github.com/isaquebraga";
```
