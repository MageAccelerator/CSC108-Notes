
# Notes

# Index

1. Basic Language

# 1. Basic Language 

# 1.1 Hello World!

1.1.1. System Out Print

	print ("hello world")

The first statement in python is at global level. 
	unlike java which always start with main ().

1.1.2. Backslash to Continue in Next Line

	amount = (noTaxValue * 0.13) \ 
			+ (noTaxValue)
			
python uses backslash at the end of one line and continues onto the next line.

1.1.3. Variables 

	message = "Hello world!"
	print(message)
	
In python, we store values in variables. 
As the example shown above, a value "Hello world!" has been stored in a variable named 'message'.

1.1.4. Strings

	"Hello world!"
	
In python, everything in "" or '' is a string.

Some methods are used to change the case of a string:

   > title() 
   
	message = "hello world!"
	print(message.title())
	
   in this case, we used title method and we will get an output as:
   
   	Hello Word!

   Method是python可对数据执行的操作。Variable后面的(.)让python对variable执行method title()指定的操作。
   
   每个method后面都跟着一对括号，因为method通常需要额外的信息来完成工作。function title()不需要额外的信息，因此括号为空。

   > upper()
   
   > lower()
   
   
1.1.4.1 Combine Strings

when we combine two strings in a variable and print it:

	message_1 = "Hello"
	message_2 = "world!"
	full_message = message_1 + " " + message_2
	
	print(full_message)
	
  we will get:
  
  	Hello world!
	

