# 20-counting-words-alechavez26
20-counting-words-alechavez26 created by GitHub Classroom
/*
 * This program counts the number of words that are in a string.
 *
 * Alejandra Chávez Cruz
 * A01411970@itesm.mx
 * 18/oct/18
 */
#include <stdio.h>



    int main() {
        //Variables
        char string[100];
        int cont= 1;
        int words=0;


            // the program ask to the user for a string
            printf(" write a string: ");
            fgets(string, sizeof(string), stdin);


            while (string[cont] != '\0') {
                cont++;
                if (string[cont] == ' '){
                    words++;
                }
            }

            //the result
            printf("Your string has %i words.", words);

            return 0;
        }
