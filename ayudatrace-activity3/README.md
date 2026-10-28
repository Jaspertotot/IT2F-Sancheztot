# AyudaTrace - Activity 3: Admin update role/status with input validation

## Run (terminal)
    mvn compile exec:java

## Run (IntelliJ)
Open the folder (it detects pom.xml), let Maven import, then run `com.ayudatrace.Main`.

Requires JDK 17 or newer. The database file `ayudatrace.db` is created in the project folder on first run.
Default admin created on first run: `admin` / `admin123`.

## Proof of execution
1. Log in as admin, choose 4. Type letters for the ID, then an invalid role, to show re-prompting. Then update another user (e.g. STAFF + APPROVED). Screenshot the whole terminal.
2. Open ayudatrace.db, users table, screenshot that user's row with the same role and status.
