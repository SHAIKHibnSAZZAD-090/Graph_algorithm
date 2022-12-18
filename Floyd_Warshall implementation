#include<bits/stdc++.h>
using namespace std;
#define INF 999 
#define n 5
void floyed(int graph[][n])
{
    int i,j,k;
    for(k=0;k<n;k++)
    {
        for(i=0;i<n;i++)
        {
            for(j=0;j<n;j++)
            {
                if(graph[i][j]>graph[i][k]+graph[k][j])
                {
                    graph[i][j]=graph[i][k]+graph[k][j];
                }
            }
        }
    }
    for(i=0;i<n;i++)
    {
        for(j=0;j<n;j++)
        {
            cout<<graph[i][j]<<" ";
        }
        cout<<endl;
    }
}
int main()
{
   int graph[n][n]= {{0,3,8,INF,-4},
                 {INF,0,INF,1,7},
                {INF,4,0,INF,INF},
                {2,INF,-5,0,INF},
                {INF,INF,INF,6,0}};
            floyed(graph);
    
}
