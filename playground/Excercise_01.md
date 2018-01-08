## Exercise_01
* Switch two variables in 3 ways.
* 三种交换值的方法。
* Give an example to express the difference between "static" and "const" variables.
* 举例说明什么是静态变量，什么是常量。
* Figure out the error(s) existed below.
* 找出错误。
Code:

			int main()
			{
				const int x = 1;
				int b = 10;
				int c = 20;

				const int* a1 = &b;
				int* const a2 = &b;
				const int* const a3 = &b;

				x = 2;
				a1 = &c;
				*a1 = 1;
				a2 = &c;
				*a2 = 1;
				a3 = &c;
				*a3 = 1;
				return 0;
			}

* Two ways to swap sentences in two char variables below
* 写出两种函数传值的方法
Code:

			char const *ap = "hello";
			char const *bp = "how are you?";
			// hint
			swap(ap, bp);
			swap(&ap, &bp);

* What are these? Figure out these expressions and write the comments behind each of them.
* 写出下列表达式的解释。
Code:

			int a;
			int *a;
			int **a;
			int a[10];
			int *a[10];
			int (*a)[10];
			int (*a)(int);
			int (*a[10])(int);

* Transfer numbers into strings
* 不使用库函数，将数字转换为字符串
Code:
			
			void int2str(int n, char *str) {
				// ...
			}

			int main()
			{
				int nNum = 99228;
				char p[10] = {};
				int buf[10] = {};
				int b_i = 0;
				int p_i = 0;
				int temp;

				cout << "Submit an integer: ";
				cin >> nNum;
				cout << "output: ";
				int2str(nNum, p);
				// ...
				return 0;
			}

* A Classic subject: Reverse string.
* 反转字符串
Code:

			void RevStr(char *src){
				// ...
			}
			int main()
			{
				char src[] = "I am from Shanghai";
				cout << src << endl;
				RevStr(src);
				cout << src << endl;
				return 0;
			}

* This is an encoded password: "Kzonft", find a one to decode it.
* 已知秘文：”Kzonft"， 尝试将其破解。
* 9X9 without repeated equation
* 九九乘法表
* The "Well Grids" game
* 井字游戏






























