# astro-be

<!-- db connection
port


POST /v1/movies

JSON body -> empty body, syntax error, type error, max body size (400 bad req)

valid body -> (422 unprocessable entity)

db call -> INSERT INTO
 . expected errors
 . unexpected errors (500 internal server error)

res -> 201 (created)

.env, environment variable

CHECK age BETWEEN 18 20

RATE LIMITING
GRACEFUL SHUTDOWN

PAGINATION -> /v1/movies?page_size=20&page=1 -> LIMIT page_size OFFSET 
(page - 1) * page_size

current_page -> 2
first_page -> 2
last_page ->  -->
<!-- total_records -> 100 / page_size -->