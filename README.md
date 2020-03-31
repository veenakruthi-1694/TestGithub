TestGithub

Description of linkedlist

code to create a linkedlist

for creating a linked list we first define the structure
the name of the structure is node
inside the structure there are two things data and next pointer(*next)
*next-> holds the address of the next node in the linked list

struct node
{
int data;
struct node *next;
}

Inside the main function 
we have to declare some pointer of datatype struct node for using *temp pointers in the program
In linked list there are elements taken from the user  as a input
ask user that enter the total number of nodes (means in the given linked list how many number of nodes they need)
n->total number of nodes
i->starting of the node and i wii be declared as 1.(i=1)

void main()
{
struct node *p,*temp,*start;
int n,i=1;
printf("enter the total number of nodes");
scanf("%d",&n);

creation of first node

printf("enter node number %d",i);
//This is the statement to take the first node in the libnked list
scanf("%d",&element);
//the variable element take that user input 
// for first node create a single node seperately and doesnot take in the for loop 
// and for all other nodes write in for loop
// first take the initial node

for example
element = 5
n=4

temp=(struct node *)malloc(size of(struct node));
//(size of(struct node)) takes ->12 bytes using malloc this is allocated in the memory
//(struct node *)-> typecasting
//temp will be the variable pointing to the node of datatype struct node
temp->data=element ;
temp->next=NULL;
//null it doesnot point to any node(doesnot holds any address)
p=temp;
//temp value is assigned to p and temp pointer holds the other addresses in furture in the linked list
//assigng the permanent node p and temp is free to take other addresses
start=temp;
//for holding the address of starting nodewhich is very important to traverse the node
//we always hold the address of the starting node
//strat holds the address of the first node and it will never move,it will be at the start node till the end of this node
//assign temp to p and also temp to start

for creation of second node 

for(i=2;i<=n;i++)
{
ptintf("enter the node number %d",i);
scanf("%d",&element); 
temp=(struct node*)malloc(size of(struct node));
temp->data=element;
temp->next=NULL;
//these 5 lines are similar(bcoz the input taking procedure and creation of node procedure are same)

 for example
element=6

p->next=temp;
//p and the next pointer of p will now point to temp
//temp is new node
// it will hold the address of next node
p->p=next;
//p should go to the next node(bcoz when p goes to next node temp variable will free)
//temp is free to take address of the next node, when p moves to the next node and holds the address of temp node here
//now p holds the address of temp node,temp variable is free to take the address of next node furture in linkedlist


