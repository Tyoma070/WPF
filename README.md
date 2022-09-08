using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows;
using System.Windows.Controls;
using System.Windows.Data;
using System.Windows.Documents;
using System.Windows.Input;
using System.Windows.Media;
using System.Windows.Media.Imaging;
using System.Windows.Navigation;
using System.Windows.Shapes;

namespace WpfApp1
{
    /// <summary>
    /// Interaction logic for MainWindow.xaml
    /// </summary>
    public partial class MainWindow : Window
    {
        public MainWindow()
        {
            double w;
            double a = double.Parse(Console.ReadLine());
            Console.Write("Ввод параметра a: ");
            double r = double.Parse(Console.ReadLine());
            Console.Write("Ввод радиуса r: ");
            w = ((3.14 * 4 / 3 * Math.Pow(r, 3)) / (Math.Pow(a, 3)));

            
        }
    }
}
