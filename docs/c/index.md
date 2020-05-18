# Код приложения
## Код программы 

```private void Form1_Paint(object sender, PaintEventArgs e)  <br>
        {  <br> 
            Point[] points =  
                {  
                new Point(300, 40),  
                new Point(250, 90),  
                new Point(270, 90),  
                new Point(200, 160),  
                new Point(220, 160),  
                new Point(130, 250),  
                new Point(470, 250),  
                new Point(380, 160),  
                new Point(400, 160),  
                new Point(330, 90),  
                new Point(350, 90),  
               };  
            e.Graphics.DrawPolygon(Pens.Green, points);  
            e.Graphics.FillPolygon(Brushes.Green, points);  
            //ствол  
            e.Graphics.DrawRectangle(Pens.Brown, 265, 250, 70, 40);  
            e.Graphics.FillRectangle(Brushes.Brown, 265, 250, 70, 40);  
            //гирлянда  
            e.Graphics.DrawEllipse(Pens.White, 272, 77, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 272, 77, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 287, 84, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 287, 84, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 302, 91, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 302, 91, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 317, 98, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 317, 98, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 332, 105, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 332, 105, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 244, 113, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 244, 113, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 259, 120, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 259, 120, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 274, 127, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 274, 127, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 289, 134, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 289, 134, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 304, 141, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 304, 141, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 319, 148, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 319, 148, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 334, 155, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 334, 155, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 349, 162, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 205, 192, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 220, 199, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 220, 199, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 235, 206, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 235, 206, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 250, 213, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 250, 213, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 265, 220, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 265, 220, 15, 15);  
            e.Graphics.DrawEllipse(Pens.White, 280, 227, 15, 15);  
            e.Graphics.FillEllipse(Brushes.White, 280, 227, 15, 15);  
        }```

(c) KatrinRain, 2020 г. 
