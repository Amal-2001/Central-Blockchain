Transaction.java
============
all inclusive bundle com.test;

public connection point Transaction identityentification
* @return the identityentification of the exchange
*/
int getTransactionId();
/
* Returns the purchaser's first call
* @return the essential call
*/
String getFirstName();
/
* Returns the purchaser's end call
* @return the end call
*/

String getLastName();
/
* Returns the exchange portrayal
* @return the depiction
*/
String getDescription();

void computeHash(int identityentification,String firstName,String lastName);
}

Block.java
========
all inclusive bundle com.test;
import java.util.Date;
/
* Block.java
* @essayist
* @essayist
* CIS 22C Lab2
*/
public grandness Block carries out Transactionnon-public int transactionId;
individual String firstName;
individual String lastName;
individual String depiction;
individual extensive timeStampMills;
individual extensive hashNextBlock;
individual static int numBlocks=0;

/
* Constructor for a Block
* @param identityentification the exchange identityentification
* @param first the buyer first call
* @param shutting the customer shutting call
* @param portrayal the exchange depiction
* Calls System's currentTimeMillis() method
* to allot the timeStampMillis
* Expands the numBlocks
*/
public Block(int identityentification,String first,String closing,String description){
transactionId = identityentification;
firstName = first;
lastName = shutting;
this.description = description;
STAMPTIMEMILL = new Date().getTime();
numBlocks++;
}
/
* Returns the contemporary scope of squares
* @return the scope of squares
*/
public static int getNumBlocks(){
return numBlocks;
}

@Supersede
public int getTransactionId() {
// Task Auto-created method stub
return transactionId;
}
@Supersede
public String getFirstName() {
// Task Auto-created procedure stub
return firstName;
}
@Supersede
public String getLastName() {
// Task Auto-created strategy stub
return lastName;
}
@Supersede
public String getDescription() {
// Task Auto-created strategy stub
return depiction;
}
/
* Ascertains the hash for the accompanying
* block
* @param identityentification coming up next square's identityentification
* @param firstName the buyer first
* require the accompanying square
* @param lastName the purchaser shutting
* call of the accompanying square
*/
@Supersede
public void computeHash(int identityentification, String firstName, String lastName) {
String call = firstName+lastName;
int total =0;
for(int i=0;i will keep set of or organization of Block Objects
* */
List blocks = new ArrayList();

/*
* breaking down current realities from enter record for example transactions.txt record
* */
String transactionId = br.readLine();
String customerName = br.readLine();
String portrayal = br.readLine();
Block = invalid;
while(transactionId!=null&&customerName!=null&&description!=null)changing String into int type
transId = Integer.parseInt(transactionId);
//Parting the given entire call into components say first and shutting
String[] call = customerName.split(" ");
//creating and setting current realities for Block Object passing required values
block=new Block(transId,call[0],call[1],description);
transactionId = br.readLine();
customerName = br.readLine();
portrayal = br.readLine();
System.out.println(block.getTransactionId()+"- - "+block.getFirstName()+"- - "+block.getLastName()+"- - "+block.getDescription());
blocks.add(block);

}

//Getting the squares records from console and fostering an
//thing of square and including to List
System.out.println("Welcome to Block Chain!");
System.out.println("Total Number of Blocks :"+block.getNumBlocks());

System.out.println("Would you need to highlight some other transaction(y/n)?:");
String decision = sc.next();

while(choice.equalsIgnoreCase("y")){

System.out.println("Enter the exchange Id:");
transId = sc.nextInt();

System.out.println("Enter the buyer first call:");
first = sc.next();
System.out.println("Enter the shopper shutting call:");
shutting = sc.next();
System.out.println("Enter exchange depiction");
depiction = sc.next();
block = new Block(transId,first,closing,description);
blocks.add(block);
System.out.println("Total Number of Blocks :"+block.getNumBlocks());
System.out.println("Would you need to highlight some other transaction(y/n)?:");
decision = sc.next();

}

System.out.println("Total Number of Blocks :"+block.getNumBlocks());
System.out.println("nter the call of the result record:");
String fileName = sc.next();

//Perusing current realities from posting and Wiriting into yield record
PrintWriter pw = new PrintWriter(new FileWriter(fileName));

Iterator itr = blocks.iterator();
ListIterator litr = blocks.listIterator();
litr.next();

while(itr.hasNext())

}
pw.println("Hash of the Next Block: 0");
pw.flush();
br.close();

}
}
###########################################
transactions.txt
==============
987684
GOLU
five heads romaine lettuce
987685
VICKY
2 pints strawberries
987686
RAJU
1 dozen oranges
987687
SANJAY
2 bundles kale
987688
RAJKUMAR
three pressing holders cherry tomatoes
945544
KANNU
1 16 ounces blueberries
945575
TANNU
1 portion whole wheat bread
945576
ALISHA
1 red cabbage
945682
LAKHAN
four honey fresh apples
945683
Slam
10 Persian cucumbers
945873
Partner Gu
2 kilos dry homestead tomatoes
945874
SHIVI
2 bundles cilantro
956689
Unforgiving
five limes
956690
RUHANA
12 red onions
942211
ROHIT
three avocado
942212
SHIVAM
five carrots
=======================
blocks.txt
============
Id:987684
Name:GOLU
description:five heads romaine lettuce
Time Stamp :1601695532675
Hash of the Next Block:11147685
Id:987685
Name:VICKY
description:2 pints strawberries
Time Stamp :1601695532676
Hash of the Next Block:12077686
Id:987686
Name:RAJU
description:1 dozen oranges
Time Stamp :1601695532676
Hash of the Next Block:6857687
Id:987687
Name:SANJAY
description:2 packs kale
Time Stamp :1601695532676
Hash of the Next Block:13047688
Id:987688
Name:RAJKUMAR
description:three pressing compartments cherry tomatoes
Time Stamp :1601695532676
Hash of the Next Block:13755544
Id:945544
Name: KANNU
description:1 half quart blueberries
Time Stamp :1601695532676
Hash of the Next Block:18275575
Id:945575
NamE:TANNU
description:1 portion whole wheat bread
Time Stamp :1601695532676
Hash of the Next Block:12155576
Id:945576
Name:ALISHA
description:1 blood red cabbage
Time Stamp :1601695532676
Hash of the Next Block:9965682
Id:945682
Name:LAKHAN
description:four honey fresh apples
Time Stamp :1601695532676
Hash of the Next Block:14425683
Id:945683
Name:RAM
description:10 Persian cucumbers
Time Stamp :1601695532676
Hash of the Next Block:6845873
Id:945873
Name:Ally Gu
description:2 kilos dry homestead tomatoes
Time Stamp :1601695532676
Hash of the Next Block:12055874
Id:945874
Name:SHIVI
description:2 bundles cilantro
Time Stamp :1601695532677
Hash of the Next Block:8936689
Id:956689
Name:HARSH
description:five limes
Time Stamp :1601695532677
Hash of the Next Block:9536690
Id:956690
Name:RUHANA
description:12 blood red onions
Time Stamp :1601695532677
Hash of the Next Block:11732211
Id:942211
NameROHIT
description:three avocado
Time Stamp :1601695532677
Hash of the Next Block:12162212
Id:942212
Name:SHIVAM
description:five carrots
Time Stamp :1601695532677
Hash of the Next Block: 0
