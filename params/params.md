# params
عند استخدام كلمة بارامز فإنها تسمح لنا بتحديد نوع البراميتيرز المره للداله

مثال :

`public static void UseParams(params int[] list)
    {
        for (int i = 0; i < list.Length; i++)
        {
            Console.Write(list[i] + " ");
        }
        Console.WriteLine();
    }`