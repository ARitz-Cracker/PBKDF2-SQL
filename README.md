# PBKDF2-SQL
This is a PBKDF2 implimentation in MySQL using HMAC-SHA512. It only takes seconds to execute!

`ARC_PBKDF2` is the function you should call. Note that you cannot set the key length, it's fixed at 64 bytes.