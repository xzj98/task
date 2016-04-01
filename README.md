# task
第一题代码

class sushu{

public void method(int a){
    boolean flag=false;
    if(a<=1){System.out.println(a+"不是素数");}
    for(int i=2;i<a;i++){
        if(a%i==0) {
            flag=true;
        }
    }
    if(flag){System.out.println(a+"不是素数");}
    else{System.out.println(a+"是素数");}
    }

}

第二题

(1)groundCount是一个整形变量，指土地面积。
   groundPrice是一个浮点型变量，指相应土地面积对应的价格。
   numberBought是一个整形变量，指购买的数量。
(2)类是对象的蓝图，根据类创造出的对象都会有自己的实例变量，例如这段代码中的name就是一个实例变量。类是可以重复使用的，类与类之间可以继承，可以使用已定义类中的方法和变量。一个类里面可以有多个方法，方法之间的信息可以互相传递，其中相同变量的值也是一样的。
(3)我认为这个程序可以让买房的人输入不同地方房子的面积和价格，他就会得到房屋的购买面积，总共花费，单位面积价格等参数，方便其进行对比，选择购买。也可以是房地产公司的人用来计算不同地段房子的价格，用来公示给顾客。
