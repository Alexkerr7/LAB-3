public class Lab3 {

        public static void main(String[] args) {
            System.out.println((20 / 4)  + "  :  " + (divide(20, 4)));

        }

        private static int add ( int x, int y)
        {
            int result = 0;
            for (int i = 0; i < x; i = i + 1)
                result = result + 1;

            for (int i = 1; i <= y; i = i + 1)
                result = result + 1;

            return result;
        }
        private static int subtract ( int x, int y)
        {
            int result = add(x, 0);

            for (int i = 0; i < y; i = i + 1)
                result = result - 1;

            return result;
        }
        private static int multiply ( int x, int y)
        {
            int result = 0;
            for (int i = 0; i < x; i = i + 1)
                result = result + y;
            return result;
        }
        private static int divide ( int x, int y)
        {
            int result = 0;
            for (int i = x; i >= y; i = i - y )
                result = result + 1;
            return result;
        }


}
