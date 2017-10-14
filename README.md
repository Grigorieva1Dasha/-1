#include <iostream>
using namespace std;
int main(void)
{
    int a,b,c,d,e,f,g,h;
    cout<<"Pologi vlevo a,b,c,d i vpravo e,f,g,h\n";
    cout<<"Vzves";
    cin>>a;
      if (a==1) {cout<<"Iz pravoi uberi f,g,h, iz levoi perelogi c i d vpravo, vlevo pologi i.Vzves";
        cin>>b;
        if (b==1) {cout<<"Vzves a i b";
          cin>>d;
          if (d==-1) {cout<<"Otvet b";};
          if (d==0) {cout<<"Otvet e";};
          if (d==1) {cout<<"Otvet a";};};
        if (b==0) {cout<<"Sravni f,g,h,vzves f i g";
          cin>>e;
          if (e==0) {cout<<"Otvet h";};
          if (e==-1) {cout<<"Otvet f";};
          if (e==1) {cout<<"Otvet g";};};};
          
      if (a==-1) {cout<<"Vzves c i d";
        cin>>f;
        if (f==1) {cout<<"Otvet c";};
        if (f==-1) {cout<<"Otvet d";};};
        
      if (a==0) {cout<<"Ubery e,c,d sprava,postav i,g,k,vpravo postav d.Vzves";
        cin>>c;
        if (c==1) {cout<<"Sravni i,g";
          cin>>g;
          if (g==0) {cout<<"Otvet k";};
          if (g==1) {cout<<"Otvet g";};
          if (g==-1) {cout<<"Otvet i";};};
        if (c==0) {cout<<"Otvet l";};
        if (c==-1) {cout<<"Sravni i,g, esli oni =, to otvet k, esli ne =, to otvet tiagelaia iz nih";
          cin>>h;
          if (h==0) {cout<<"Otvet k";};
          if (h==1) {cout<<"Otvet i";};
          if (h==-1) {cout<<"Otvet g";};};
          return 0;
    }}
