Hacked and compiled cg-brutaltester with hacked and compiled Code of Kutulu referee for your enjoyment.
https://github.com/dreignier/cg-brutaltester
https://github.com/pedouard/cotc-referee

Example run, substitute -p1 :
java -jar .\cg-brutaltester-1.0.0-SNAPSHOT.jar -r "java -jar codeOfKutulu-1.0.jar" -p1 "python -u kt.py" -p2 "python -u kt_2impr.py" -p3 "python -u kt_217g.py" -p4 "python -u kt_190g.p
y" -t 2 -n 24 -s -v -l "./logs/"

Or you can use example players from CoK unit tests:
java -jar .\cg-brutaltester-1.0.0-SNAPSHOT.jar -r "java -jar codeOfKutulu-1.0.jar" -p1 "java -cp . runner.tests.random.Player" -p2 "java -cp . runner.tests.random.Player" -p3 "java -cp . runner.tests.uselight.Player" -p4 "java -cp . runner.tests.yell.Player" -t 2 -n 24 -s -v -l "./logs/"
