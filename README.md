#include <stdio.h>
#include <stdlib.h>

int main(void) {
    int chosen_minutes = 1141;
    int days = chosen_minutes/1140;
    int hours = (chosen_minutes-days*1140)/60;
    int minutes =chosen_minutes-((hours*60)+(days*1140));
     printf("%dm -> %dd %dh %dm",chosen_minutes,days, hours,minutes );
    return EXIT_SUCCESS;
}
