# FAQ
1. **Question** <br />
   How to resolve Ssl error on Cygwin when try to access Github remote branches? <br />
   **Answer** <br />
   Since IDEA's Github plugin not support proxy very well, please add below settings to your `.git/config` file to avoid SSL error when try to push/pull/fetch.  **After setup this please remember run GoAgent when try to access git remote.** <br />
    >[http] <br />
             proxy = http://127.0.0.1:8087 <br />
             sslVerify = false