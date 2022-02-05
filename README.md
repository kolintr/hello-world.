# hello-world.
one repository

    /*
Задача по алгоритмам Ӏ Java Syntax: 5 уровень, 12 лекция
*/

    public class Solution {
        public static void main(String[] args) throws Exception {
            BufferedReader reader = new BufferedReader(new InputStreamReader(System.in));
            int maximum = Integer.parseInt(reader.readLine());

            if (maximum > 0){
                int value = Integer.parseInt(reader.readLine());

                for (int i = 0; i < maximum - 1; i++){
                    int number = Integer.parseInt(reader.readLine());

                    if (value < number){
                        value = number;
                    }
                }
                System.out.println(value);
            }
        }
    }
