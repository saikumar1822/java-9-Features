# java-9-Features
private methods inside an interface is allowed to help the common code share between the non abstarct methods

private static methods also allowed in java 9 interface

try with resource enhancement it is there in java 7 also but there is limitation that we need to declare resource within the locally with in its block
ex : try(fileOutPutstream fos=new fileOutPutStream("abc.txt"))

in java 9 we can declare out side the try block and use the refernece within try
fileOutPutstream fos=new fileOutPutStream("abc.txt")
try(fos)

diamond operator in anonymous innerclass

in java 7 @safeVarargs annotation can only be appiled on final methods,static methods and constructors
from java 9 it can also be used with Private instance methods

java 9 factory methods
list.of("java","jfj","jjf");


java 9 Stream Api improvement

takeWhile() method in stream returns the elements that matches 
if the first element itself does not match with the condition then take while method will stop there itslef

dropWhile()->returns a stream that contains remaining elements of the stream after dropping elements that doesnt match with predicate

Stream.Iterate()
Stream.iterate(1,i->i<=10,i->i*3).forEach(sysout);

in java 7 we use underscore as identfier ,variable
but in java 9 it is used as keyword .hence we can not use (_) as varible and identifier
