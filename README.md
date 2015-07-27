# oasis-content
Content of Oasis project (FitnesseRoot) to be separate from project itself

To run Oasis, make sure the fitnesse.jar file is present in the directory and type:

java -jar fitnesse.jar -d . -p 8000 -o -e 0

To run Oasis with the FitnesseRoot outside of the default directory, the -r <path to FitnesseRoot> flag must be specified (inclusive) e.g.

-r ..\oasis-content\FitNesseRoot

if the oasis-content repo has been checked out at the same level as the OASIS-Maven repo
