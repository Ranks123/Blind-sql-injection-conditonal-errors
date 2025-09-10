# Blind-sql-injection-conditonal-errors
A Python script that automates blind SQL injection to extract the administrator’s password from a vulnerable web app. It uses error-based injection (TO_CHAR(1/0)) and detects valid characters by monitoring HTTP 500 responses, building the password one character at a time.
