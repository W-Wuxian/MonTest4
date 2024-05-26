# MonTest4
#include <stdio.h>
i,x,y,cx,cy,dx,dy,nb,f[8][16],b[8][16];
main()
{
    f[0][1] = 2;//1
    f[1][2] = 1;
    f[2][0] = 1;
    f[2][1] = 1;
    f[2][2] = 1;
    for(i=0;i<2;++i){
        for(cy=0;cy<8;++cy){
            for(cx=0;cx<16;++cx){
                printf("%d %d %d %c\n", cy,cx,f[cy][cx],"ABC"[f[cy][cx]]);
                 //printf("%c", ".#"[f[cy][cx]]);
            }
            
        }
    }
    return 0;
}
