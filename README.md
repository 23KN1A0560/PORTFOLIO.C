#include <stdio.h>

int main() {
    char name[50];
    char skills[200];
    char bio[300];

    printf("===== WELCOME TO YOUR PORTFOLIO =====\n\n");

    // Get user input
    printf("Enter your name: ");
    fgets(name, sizeof(name), stdin);

    printf("Enter your skills (comma-separated): ");
    fgets(skills, sizeof(skills), stdin);

    printf("Write a short bio: ");
    fgets(bio, sizeof(bio), stdin);

    // Display portfolio
    printf("\n=====================================\n");
    printf("            MY PORTFOLIO             \n");
    printf("=====================================\n");
    printf("Name      : %s", name);
    printf("Skills    : %s", skills);
    printf("Bio       : %s", bio);
    printf("=====================================\n");

    return 0;
}


