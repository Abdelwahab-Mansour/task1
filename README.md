1-عشان استخدمنا Standard Numeric Format Specifier من نوع C دي بتشتغل علي تنسيق العملة رمز $ و رقمين بعد العلامة 

2-بتعمل تنسيق جاهز للارقام زاي C = عرض العملات , N = عرض الارقام بفواصل , P = عرض نسبة مئوية , F = بتحدد عدد الارقام بعد العلامة

3-int X = 10;

int Y = 20;

Console.WriteLine($"Multiplication : {X} * {Y} = {X*Y:F4}");

output = Multiplication : 10 * 20 = 200.0000
