CodeforcesCrawler
Web crawler that downloads all unique, successul and public solutions of a user on Codeforces.

Usage Instructions:
Add CodeforcesCrawler.jar from the repository.

$ java -jar CodeforcesCrawler.jar <username>

Example:
$ java -jar CodeforcesCrawler.jar azzy

Features:
Fetches a single AC solution for each of the problems.

Fetches the latest AC solutions for all problems.

It times the entire process, to give exact runtime of the crawling performed.

Provides clear output statements to keep the user aware about progress being made, while downloading solutions.

Supports downloading JAVA, CPP, C and PYTHON codes, since these are the most used. Rest are downloaded without any file extension.

