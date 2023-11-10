# Лабораторная по ТРПО
<div style="width: 100%;">
    <img src="header.svg" width="800" height="300">
</div>

## Меню
1. Нахождения корней
1. Нахождения корней
```C#
   quadraticEquations1.a = Convert.ToDouble(A.Text);
   quadraticEquations1.b = Convert.ToDouble(B.Text);
   quadraticEquations1.c = Convert.ToDouble(C.Text);
   X1.Text = quadraticEquations1.root1;
   X2.Text = quadraticEquations1.root2;
   public string root1{ 
            get{
                double D = b * b - 4 * a * c;
                return D >= 0 ? ((-b + Math.Sqrt(D)) / (2 * a)).ToString():$"{-b / (2 * a)} + {Math.Sqrt(-D) / (2 * a)}i";
            } 
        }
        public string root2
        {
            get
            {
                double D = b * b - 4 * a * c;
                return D >= 0?((-b - Math.Sqrt(D)) / (2 * a)).ToString(): $"{-b / (2 * a)} - {Math.Sqrt(-D) / (2 * a)}i";
            }
        }
```
