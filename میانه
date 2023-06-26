namespace ConsoleApp12
{
    internal class Program
    {
        static void Main(string[] args)
        {
            int i, j;
            int[,] medi = new int[3, 3];
            for (i = 0; i < 3; i++)
            {
                for (j = 0; j < 3; j++)
                {
                    Console.WriteLine("ENTER THE [" + i + "," + j + "] : ");
                    medi[i, j] = Convert.ToInt32(Console.ReadLine());
                }
            }



            medi[1, 1] = (medi[0, 0] + medi[0, 1] + medi[0, 2] + medi[1, 0] + medi[1, 2] + medi[2, 0] + medi[2, 1] + medi[2, 2]) / 8;


            Console.WriteLine("  the average of array is  : " + medi[1, 1]);
        }
    }
}
