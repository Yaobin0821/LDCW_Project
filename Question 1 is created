#include <iostream>
#include <cctype>
using namespace std;

bool isValidOption(char option) {
    option = tolower(option);
    return option == 'a' || option == 'b' || option == 'c' || option == 'd';
}

char getValidatedAnswer() {
    char answer;
    while (true) {
        cin >> answer;
        if (isValidOption(answer)) {
            return tolower(answer);
        } else {
            cout << "Invalid input. Please enter only A, B, C, or D: ";
        }
    }
}

int main() {
    int score = 0;
    char answer;

    cout << "=== Are You Digitally Safe? A 10-Question Cybersecurity Quiz ===\n";
    cout << "Answer each question by typing A, B, C, or D (not case-sensitive)\n\n";

    cout << "1. What is the safest way to store your passwords?\n";
    cout << "A. Use the same password for all accounts\n";
    cout << "B. Use a password manager\n";
    cout << "C. Write them down on paper\n";
    cout << "D. Memorize simple passwords\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'b') score++;

    cout << "\n2. What does '2FA' stand for?\n";
    cout << "A. Two-Factor Authentication\n";
    cout << "B. Twice Fast Access\n";
    cout << "C. Two-Fold Authorization\n";
    cout << "D. Twin File Agreement\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'a') score++;

    cout << "\n3. You receive an email from your bank asking for your login details. What should you do?\n";
    cout << "A. Reply with your username and password\n";
    cout << "B. Click the link and login immediately\n";
    cout << "C. Ignore or report the email as phishing\n";
    cout << "D. Call your friend to ask what to do\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'c') score++;

    cout << "\n4. Which password is the strongest?\n";
    cout << "A. mypassword\n";
    cout << "B. abc123\n";
    cout << "C. !T8g$k@1Qm#z\n";
    cout << "D. qwerty\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'c') score++;

    cout << "\n5. What’s the risk of using public Wi-Fi for online banking?\n";
    cout << "A. No risk\n";
    cout << "B. It’s slower\n";
    cout << "C. It can be intercepted by hackers\n";
    cout << "D. Only risky if it's night time\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'c') score++;

    cout << "\n6. What is a phishing scam?\n";
    cout << "A. An online game cheat\n";
    cout << "B. A fake message to steal personal info\n";
    cout << "C. A computer virus\n";
    cout << "D. A type of firewall\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'b') score++;
    
    cout << "\n7. What should you do before clicking on a link in a suspicious email?\n";
    cout << "A. Click to check where it leads\n";
    cout << "B. Hover over the link to preview the URL\n";
    cout << "C. Forward it to friends\n";
    cout << "D. Ignore and delete without checking\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'b') score++;

    cout << "\n8. What kind of websites should you avoid entering personal information into?\n";
    cout << "A. Websites with HTTPS and a lock icon\n";
    cout << "B. Government websites\n";
    cout << "C. Websites without HTTPS or a lock icon\n";
    cout << "D. Online stores like Amazon\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'c') score++;

    cout << "\n9. Which one of these is considered a secure login habit?\n";
    cout << "A. Logging into accounts from public computers\n";
    cout << "B. Saving passwords in browser without protection\n";
    cout << "C. Using 2FA and private devices\n";
    cout << "D. Giving credentials to family\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'c') score++;

    cout << "\n10. How often should you change your passwords?\n";
    cout << "A. Only when you forget them\n";
    cout << "B. Every few months or after a breach\n";
    cout << "C. Never\n";
    cout << "D. Every week\n";
    cout << "Your answer: ";
    answer = getValidatedAnswer();
    if (answer == 'b') score++;

    cout << "\nYou scored " << score << "/10.\n";

    if (score >= 8) {
        cout << "Cybersecurity Level: HIGH" << endl;
        cout << "You're well-protected and understand online safety!" << endl;
    } else if (score >= 5) {
        cout << "Cybersecurity Level: MEDIUM" << endl;
        cout << "You know the basics, but there’s room to improve." << endl;
    } else {
        cout << "Cybersecurity Level: LOW" << endl;
        cout << "You need to learn more about staying safe online!" << endl;
    }

    return 0;
}
