# Blockchain Basics
## Genesis Block
Some Basics of Blockchain !!  
Genesis Block  
{  
    index: 0,  
    timestamp: current time,  
    data: "iam the genesis block",  
    proof: 3,  
    previous_hash: "0"  
} -> hash() -> 2233aaa2  
  
{  
    index: 1,  
    timestamp: current time,  
    data: "hello world",  
    proof: 2134,  
    previous_hash: 2233aaa2  
} -> hash() -> 67674zzz  
  
{  
    index: 2,  
    timestamp: current time,  
    data: "subscribe xyz",  
    proof: 989876,  
    previous_hash: 67674zzz  
}  
  
proof ?  
Output of some computation OR some mathematical computation output OR output of some conditions  
  
previous hash ?  
Hashed complete previous node   
  
Hash ?  
digest complete node to generate 1 unique. Unique identifier  
