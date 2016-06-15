import java.util.Scanner;

class SwitchTest2 {
	public static void main(String[] args) {
		//出一个选择题，然后供你选择。
		//由于我们现在没有办法键盘录入得到一个'A','B'
		//这样的东西，我就用65，66这样的值替代
		//将来我们获取到这样的值以后，强制转换为字符类型
		System.out.println("下面的几个人你最爱谁?");
		System.out.println("65 林青霞");
		System.out.println("66 张曼玉");
		System.out.println("67 刘德华");
		System.out.println("68 王力宏");
		啦啦啦打大师
						
/*
this is for daily life.
	
	其实它的作用不是结束循环的，而是结束方法的。
*/


		Scanner sc = new Scanner(System.in);
		
		System.out.println("请输入你的选择：");
		int choiceNumber = sc.nextInt();
		String text = "hello";
		//强制转换为字符类型
		char choice = (char) choiceNumber;
		
		switch(choice) {
			case 'B':
				System.out.println("不好意思，你选择有误");
				break;
			case 'C':
				System.out.println("不好意思，你选择有误");
				break;
			case 'D':
				System.out.println("不好意思，你选择有误");
				break;
			case 'E':
				System.out.println("we are out");
				break;
			default:
				System.out.println("没有该选项");
				break;
		}
	}
}


Life is running now!
