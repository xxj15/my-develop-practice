import java.util.*;

public class RockPaperScissors {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        String[] choices = {"가위", "바위", "보"};
        Random random = new Random();

        System.out.print("가위, 바위, 보 중 하나를 입력하세요: ");
        String userChoice = scanner.nextLine();

        if (!Arrays.asList(choices).contains(userChoice)) {
            System.out.println("잘못된 입력입니다.");
            return;
        }

        String computerChoice = choices[random.nextInt(3)];
        System.out.println("컴퓨터: " + computerChoice);

        if (userChoice.equals(computerChoice)) {
            System.out.println("비겼습니다!");
        } else if (
            (userChoice.equals("가위") && computerChoice.equals("보")) ||
            (userChoice.equals("바위") && computerChoice.equals("가위")) ||
            (userChoice.equals("보") && computerChoice.equals("바위"))
        ) {
            System.out.println("이겼습니다!");
        } else {
            System.out.println("졌습니다!");
        }
    }
}


}
