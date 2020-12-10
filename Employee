import java.util.Scanner;
public abstract class Employee {
	public int lasary;
	public abstract void ComputeEmp();
	public static void main(String[] args) {
		Manager M = new Manager();
		M.ComputeEmp();
		Salesman S = new Salesman();
		S.ComputeEmp();
		Worker W = new Worker();
		W.ComputeEmp();
	}
}

class Manager extends Employee{
	public void ComputeEmp() {
		lasary = 5000;
		System.out.println("经理的月薪为："+lasary);
	}
}

class Salesman extends Employee{
	public void ComputeEmp() {
		Scanner in=new Scanner(System.in);
		int basiclasary = 3000;
		System.out.println("请输入销售人员这个月的销售件数：");
		int num = in.nextInt();
		lasary = basiclasary + num*20;
		System.out.println("销售人员这个月的销售件数为："+num);
		System.out.println("销售人员的月薪为"+lasary);
	}
}

class Worker extends Employee{
	public void ComputeEmp() {
		Scanner in=new Scanner(System.in);
		System.out.println("请输入普通工人这个月的上班天数：");
		int day = in.nextInt();
		lasary=day*100;
		System.out.println("普通工人这个月的上班天数为："+day);
		System.out.println("普通工人的月薪为："+lasary);
	}
}
