#include <iostream>
using namespace std;

int main()
{
    int A, amount, balance, milk, gram, sugar, coffee;
    
    cout<<"WELL, YOU MIGHT BE FELLING TIRED FOR NOW"<<endl<<endl;
    cout<<"WOULD YOU LIKE TO HAVE A CUP OF COFFEE!"<<endl<<endl;
    cout<<"ENTER 1 FOR'YES'.\nENTER 0 FOR 'NO'."<<endl;
    cin>>A;
    
    if(A == 1){
        cout<<"SO....LET'A START MAKING A COFFEE FOR YOURSELF :)"<<endl<<endl;
         
        cout<<"FIRST OF ALL WE NEED TO BUY INGREDIENTS WHICH WILL BE NEEDED TO MAKE A COFFEE."<<endl<<endl; 
        
        cout<<"HOW MUCH MONEY DO YOU HAVE RIGHT NOW IN YOUR POCKET?"<<endl;
        cin>>amount;
        cout<<"WELL YOU HAVE "<<amount<<"$ WITH YOU"<<endl<<endl;
        
        cout<<"\t\t.........WELLCOME TO RICH SUPER MALL..........."<<endl<<endl;
        
        //BUYING INGREDIENTS - MILK.
        
        cout<<"HOW MUCH AMOUNT OF MILK YOU WANT?"<<endl<<endl;
        cout<<"PRICE OF MILK"<<endl;
        cout<<"1000ML = 10$\n900ML = 9$\n800ML = 8$\n700ML = 7$\n600ML = 6$\n500ML = 5$\n400ML = 4$\n300ML = 3$\n200ML = 2$\n100ML = 1$"<<endl<<endl;
        cout<<"ENTER THE AMOUNT OF MILK YOU WANT."<<endl;
        cin>>milk;
        
        balance = amount - milk;
        gram = milk * 100;
        cout<<"WELL YOU PURCHED "<<gram<<"ML OF MILK."<<endl<<endl;
        cout<<"SO YOU ARE LEFT WITH "<<balance<<"$ MONEY WITH YOU."<<endl<<endl;
        
        //BUYING INGREDIENTS - SUGAR.
        
        cout<<"HOW MUCH AMOUNT OF SUGAR YOU WANT?"<<endl<<endl;
        cout<<"PRICE OF SUGAR"<<endl;
        cout<<"100g = 10$\n90g = 9$\n80g = 8$\n70g = 7$\n60g = 6$\n50g = 5$\n40g = 4$\n30g = 3$\n20g = 2$\n10g = 1$"<<endl<<endl;
        cout<<"ENTER THE AMOUNT OF SUGAR YOU WANT."<<endl;
        cin>>sugar;
        
        balance = balance - sugar;
        gram = sugar * 10;
        cout<<"WELL YOU PURCHED "<<gram<<"g OF SUGAR."<<endl<<endl;
        cout<<"SO YOU ARE LEFT WITH "<<balance<<"$ MONEY WITH YOU."<<endl<<endl;
        
        //BUYING INGREDIENTS - COFFEE PACKET.
        
        cout<<"HOW MUCH AMOUNT OF COFFEE PACK YOU WANT?"<<endl<<endl;
        cout<<"PRICE OF COFFEE PACK"<<endl;
        cout<<"1PACK = 1$"<<endl<<endl;
        cout<<"ENTER THE AMOUNT OF COFFEE PACK YOU WANT."<<endl;
        cin>>coffee;
        
        balance = balance - coffee;
        gram = coffee * 1;
        cout<<"WELL YOU PURCHED "<<gram<<" COFFEE PACKET."<<endl<<endl;
        cout<<"SO YOU ARE LEFT WITH "<<balance<<"$ MONEY WITH YOU."<<endl<<endl;
        
        cout<<"AHH...FINALLY WE ARE DONE WITH BUYING INGREDIENTS"<<endl<<endl;
        
        cout<<"SO LET'S START WITH THE MAKING OF COFFEE"<<endl<<endl;
        
        
        
        
        
         
    }
     else if(A == 0){
            cout<<"HMM...IT SEEMS LIKE YOU ARE NOT IN A MOOD OF COFFEE :("<<endl<<endl;
    }
        
     else{
        cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTION :("<<endl<<endl;
    }
    
    return 0;
}
