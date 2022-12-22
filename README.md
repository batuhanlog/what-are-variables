PATİKA.DEV
what are variables in summary

Variables are named storage locations that can have their values changed during the execution of a program. Variables have a type, which determines the type of values that they can hold. For example, an integer variable can hold an integer such as 5, while a string variable can hold a sequence of characters such as "hello". 

Değişkenler, bir program sırasında değerlerinin değiştirilebileceği adlandırılmış depolama konumlarıdır. Değişkenlerin bir türü vardır ve bu tür, değişkenlerin tutabileceği değerlerin türünü belirler. Örneğin, bir tamsayı değişkeni 5 gibi bir tamsayı tutabilir, iken bir dize değişkeni "merhaba" gibi bir dizi karakter tutabilir.

Örnek Kodlar : 

            byte b = 5;         //1 byte
            sbyte sb = 5;        //1 byte
            short s = 5;        //2 byte
            ushort us = 5;       //2 byte

            Int16 i16 = 2;      //2 byte
            int i = 2;          //4 byte
            Int32 i32 = 2;      //4 byte
            Int64 i64 = 2;      //8 byte
            uint ui = 2;        //4 byte
            long l = 2;         //8 byte
            ulong ul = 2;        //8 byte

            float f = 5;        //4 byte
            double d = 5.4;     //8 byte

            char c = 'a';       //2byte
            string str = "Ömür"; 

            bool bl = false;

            DateTime dt = DateTime.Now;   
            Console.WriteLine(dt);

            object o1 = "x";    //string
            object o2 = 'y';    //char
            object o3 = 4.5;    //decimal
            object o4 = 6;      //integer
           
            string str1 = string.Empty;
            string str2 = null;
            string str3;

            string strName = "batuhan";
            string name = "batuhan";
            string surname = "kayahan";
            string fullname = name + " " + surname;

            Console.WriteLine(strName);
            Console.WriteLine(fullname);

            
            int int1 = 5;
            int int2 = 3;
            int in3 = int1 * int2;

        
            bool b1 = 10 > 2;

            //  Değişken Dönüşümleri 

            // int.Parse(int1) 
            // Convert.ToInt32(dönüştürülecek);
               
            
            string str20 = "20";
            int int20 = 20;
            string str4 = str20 + int20.ToString(); 

            Console.WriteLine(str4);   

         
            // int20.ToString() 
            // Convert.ToString(int20);


            int int3 = int20 + Convert.ToInt32(str20);  
            
