#include <iostream>
using namespace std;

int main()
{
    int A, balance, milk, milkgram ,sugargram, coffeegram, sugar, coffee, quantity;
    
    cout<<"WELL, YOU MIGHT BE FELLING TIRED FOR NOW"<<endl<<endl;
    cout<<"WOULD YOU LIKE TO HAVE A CUP OF COFFEE!"<<endl<<endl;
    cout<<"ENTER 1 FOR'YES'.\nENTER 0 FOR 'NO'."<<endl;
    cin>>A;
    
    if(A == 1){
        cout<<"SO....LET'A START MAKING A COFFEE FOR YOURSELF :)"<<endl<<endl;
         
        cout<<"FIRST OF ALL WE NEED TO BUY INGREDIENTS WHICH WILL BE NEEDED TO MAKE A COFFEE."<<endl<<endl; 
        
        cout<<"HOW MUCH MONEY DO YOU HAVE RIGHT NOW IN YOUR POCKET?"<<endl;
        cin>>balance;
        
    
        cout<<"WELL YOU HAVE "<<balance<<"$ WITH YOU"<<endl<<endl;
        
        cout<<"\t\t.........WELLCOME TO RICH SUPER MALL..........."<<endl<<endl;
            
        //BUYING INGREDIENTS - MILK.
        
        do{
            cout<<"PRICE OF MILK"<<endl;
            cout<<"1000ML = 10$\n900ML = 9$\n800ML = 8$\n700ML = 7$\n600ML = 6$\n500ML = 5$\n400ML = 4$\n300ML = 3$\n200ML = 2$\n100ML = 1$"<<endl<<endl;
            cout<<"ENTER THE AMOUNT OF MILK YOU WANT."<<endl;
            cin>>milk;
        if(milk > balance)
        {
            cout<<"SORRY! YOU DON'T HAVE THAT MUCH BALANCE WITH YOU :("<<endl<<endl;
            cout<<"I THINK YOU HAVE TO BUY LESS ML OF MILK"<<endl<<endl;
        }
        }
        while(milk > balance);
        
        balance = balance - milk;
        
        milkgram = milk * 100;
        cout<<"WELL YOU PURCHED "<<milkgram<<"ML OF MILK."<<endl<<endl;
        cout<<"SO YOU ARE LEFT WITH "<<balance<<"$ MONEY WITH YOU."<<endl<<endl;
        
        
        //BUYING INGREDIENTS - SUGAR.
        
        do{
            cout<<"PRICE OF SUGAR"<<endl;
            cout<<"100g = 10$\n90g = 9$\n80g = 8$\n70g = 7$\n60g = 6$\n50g = 5$\n40g = 4$\n30g = 3$\n20g = 2$\n10g = 1$"<<endl<<endl;
            cout<<"ENTER THE AMOUNT OF SUGAR YOU WANT."<<endl;
            cin>>sugar;
        if(sugar > balance)
        {
            cout<<"SORRY! YOU DON'T HAVE THAT MUCH BALANCE WITH YOU :("<<endl<<endl;
            cout<<"I THINK YOU HAVE TO BUY LESS GRAM OF SUGAR"<<endl<<endl;
        }
        }
        while(sugar > balance);
        
        balance = balance - sugar;
        
        sugargram = sugar * 10;
        cout<<"WELL YOU PURCHED "<<sugargram<<"g OF SUGAR."<<endl<<endl;
        cout<<"SO YOU ARE LEFT WITH "<<balance<<"$ MONEY WITH YOU."<<endl<<endl;
        
        //BUYING INGREDIENTS - COFFEE PACKET.
        
        do{
            cout<<"PRICE OF COFFEE PACK"<<endl;
            cout<<"1PACK = 1$"<<endl<<endl;
            cout<<"ENTER THE AMOUNT OF COFFEE PACK YOU WANT."<<endl;
            cin>>coffee;
        if(coffee > balance)
        {
            cout<<"SORRY! YOU DON'T HAVE THAT MUCH BALANCE WITH YOU :("<<endl<<endl;
            cout<<"I THINK YOU HAVE TO BUY LESS COFFEE PACKET"<<endl<<endl;
        }
        }
        while(coffee > balance);
        
        balance = balance - coffee;
        
        coffeegram = coffee * 1;
        cout<<"WELL YOU PURCHED "<<coffeegram<<"PACK OF COFFEE."<<endl<<endl;
        cout<<"SO YOU ARE LEFT WITH "<<balance<<"$ MONEY WITH YOU."<<endl<<endl;
        
        // MAKING OF COFFEE.
        
        cout<<"AHH...FINALLY WE ARE DONE WITH BUYING INGREDIENTS"<<endl<<endl;
        
        cout<<"SO LET'S START WITH THE MAKING OF COFFEE"<<endl<<endl;
        
        // STEP 1 TO MAKE COFFEE.
        
            cout<<"STEP: 1"<<endl<<endl;
        do{
            cout<<"ENTER 1 TO LIGHTUP THE STOVE."<<endl<<endl;
            cin>>A;

        if(A > 1){
        
            cout<<"SORRY! BUT YOU HAVE TO LIGHTUP THE STOVE TO MAKEA COFFEE :("<<endl<<endl;
        }
        
        }
        while(A > 1);
        
        cout<<"THAT'S GOOD! LET'S MOVE TO THE NEXT 2 STEP."<<endl<<endl;
        
        // STEP 2 TO MAKE COFFEE.
        
            cout<<"STEP: 2"<<endl<<endl;
            
        do{
            cout<<"ENTER 1 TO KEEP A VESSEL ON THE STOVE."<<endl<<endl;
            cin>>A;

        if(A > 1){
        
            cout<<"SORRY! BUT YOU HAVE TO KEEP A VESSEL ON THE STOVE IN ORDER TO MAKE A COFFEE :("<<endl<<endl;
        }
        
        }
        while(A > 1);
        
        cout<<"THAT'S GOOD! LET'S MOVE TO THE NEXT 3 STEP."<<endl<<endl;
        
        // STEP 3 TO MAKE COFFEE.
        
            cout<<"STEP: 3"<<endl<<endl;
            
        do{
            cout<<"ENTER 1 TO POUR THE MILK IN THE VESSEL."<<endl<<endl;
            cin>>A;

        if(A > 1){
        
            cout<<"SORRY! BUT YOU HAVE TO POUR THE MILK IN THE VESSEL TO MAKE A COFFEE :("<<endl<<endl;
        }
        
        }
        while(A > 1);
        
        cout<<"THAT'S GOOD! LET'S MOVE TO THE NEXT 4 STEP."<<endl<<endl;
        
        // STEP 4 TO MAKE COFFEE.
        
            cout<<"STEP: 4"<<endl<<endl;
        
        do{
            cout<<"HOW MUCH GRAM OF SUGAR YOU WANT IN YOUR COFFEE?"<<endl<<endl;
            cin>>quantity;
            
            if(quantity > sugargram){
                cout<<"SORRY! BUT YOU DON'T HAVE THAT MUCH OF SUGAR."<<endl<<endl;
            }
        }
            while(quantity > sugargram);
            
            quantity = sugargram - quantity;
            cout<<"ENTER 1 TO PUT "<<sugargram<<"g OF SUGAR IN MILK."<<endl<<endl;
            cin>>A;

        
        
        
        
        
        
        
        
        
        
        
        
        
        }
    
        // DON'T WANT COFFEE CONDITIONS.
        
        else if(A == 0){
            cout<<"HMM...IT SEEMS LIKE YOU ARE NOT IN A MOOD OF COFFEE :("<<endl<<endl;
    }
        
        else{
        cout<<"YOU MIGHT HAVE NOT FOLLOWED THE INSTRUCTION :("<<endl<<endl;
    }
        
    return 0;
}

