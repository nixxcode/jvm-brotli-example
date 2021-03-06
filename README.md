Example showing how to use jvm-brotli (https://github.com/nixxcode/jvm-brotli)

Also a great way to test if your current JVM platform is supported.

Simply clone this repository and run `mvn package` to build. If you don't have maven installed, you can use the included maven wrapper and run `mvnw package` (or `mvnw.cmd package` on Windows).

After you've run the build:

Execute the "Main" class via your favourite IDE.

**OR** 

Run `java -jar target/jvmb-example.jar` from the **project root**. (Do not go into target dir and run from there, it won't work due to hardcoded paths)

If the execution is successful, two new files should appear in the src folder: **encoded.br** and **decoded.txt**

If your system is not supported, you should get an exception that says so. If this is the case, please head on over to the jvm-brotli [issue tracker](https://github.com/nixxcode/jvm-brotli/issues) and check if a support request for your platform already exists. If not, please create one so that we can get your platform on board ASAP! :)

Thank you [@tipsy](https://github.com/tipsy) for creating the original example that I forked. :)
