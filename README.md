#pyramid<br>
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
원하는 피라미드 모양 잡기위해선 공백 넣어야함(원하는 층-현재 층)
별 찍기 공식(현재 층-1)x2-1
