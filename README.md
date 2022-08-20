patika.dev Veri Yapıları ve Algoritmalar - [Merge Sort Projesi ve Tüm projelerim](https://app.patika.dev/isakli05).
# Merge Sort
## patika.dev Veri Yapıları ve Algoritmalar - Merge Sort Projesi

## [16,21,11,8,12,22] -> Merge Sort
## 1.Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.


### sayı dizimin ilk hali 
                 [16][21][11][8][12][22]                                 
### 1.adım                    
             [16][21][11]       [8][12][22]
                             
### 2.adım
          [16]    [21][11]     [8][12]    [22]
                          
### 3.adım
    [16]   [21]    [11]          [8]  [12]  [22] 
                     
### 4.adım
        [16]    [11][21]        [8][12]      [22]
                        
### 5.adım 
             [11][16][21]     [8][12][22]
                              
### 6.adım                       
                [8][11][12][16][21][22]
                                 
## 2.Big-O Notation = O(6*(log6))                             
