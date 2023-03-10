# triangle pyramid<br>
## triangle
### for문<br>

package 자바;

import java.util.Scanner;

public class 과제 {
        public static void main(String[] args) {<br>
        	Scanner sc = new Scanner(System.in);<br>
        System.out.print("몇 단 출력 :");
	
	int num;<br>
	num = sc.nextInt();<br>
	for(int i=0;i<num;i++){
	    for(int j=0;j<=i;j++){
		System.out.print("*");
	    }
	    System.out.println("");
	}
	}
}

## 실행된 이미지<br>
![image](https://user-images.githubusercontent.com/126844692/224198086-af1ac322-0546-46ac-81cb-d5c300f41097.png)<br>
## 설명<br>
자바라는 코딩 프로그램을 사용해서 for문이라는 반복문으로 만든 작업<br>
사용자가 키보드에 입력한 값 만큼 단 수가 만들어짐<br>
## pyramid<br>
### for문<br>

package 자바;

import java.util.Scanner;

public class test1 {<br>
	public static void main(String[] args) {<br>
		// TODO Auto-generated method stub<br>
		Scanner sc = new Scanner(System.in);<br>
        System.out.print("피라미드 단 입력:");

        int num = sc.nextInt();
        for(int i =0 ; i < num; i++) {

            for(int k= 1; k< num-i; k++) {
                System.out.print(" ");
            }
            for(int j= 0; j< i*2+1; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
	}

}

## 실행된 이미지<br>
![image](https://user-images.githubusercontent.com/126844692/224194022-6534c445-6861-42d9-aa2f-9bc933ff2641.png)<br>
## 설명<br>
자바라는 코딩 프로그램을 사용해서 Scanner라는 입력문을 쓰고 for문이라는 반복문으로 만든 작업<br>
사용자가 입력한 값으로 층수를 만들고 별의 개수는<br>
별 : (현재 층-1)x2+1개가 깔리면서 피라미드를 만듦<br>
공백은 공백갯수로 모양 잡기 (내가 원하는 전체 층-현재 층)<br>
반복횟수 : 전체 층(반복문)<br>
