# Lifelong

An API to log your life. Add tasks to quickly add logs with optional notes. Add tags to query similar tasks or simple query by time. Lifelong uses mysql, and exposes a simple to use api on localhost.

## Task Structure  

  - Tags: List of String
    - Each tag must be in a valid tag under Tags
  - TimeStamp: Int
    - Stored as Time since Linux Epoc
  - Notes: String
    - Can be empty
    
## Tag Structure
  
  - Name: String
   
