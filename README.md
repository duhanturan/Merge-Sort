# Merge-Sort

## Patika-dev | Veri Yapıları ve Algoritmalar Ödevi 2

### [16,21,11,8,12,22] -> Merge Sort

- Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
>
>       [16,21]   [11]   ------   [8,12]    [22]
>
>       [11,16,21]        ----    [8,12,22]
> 
> 8, 11'den küçük olduğu için önce o yazılır. 8 den sonra kendi grubunda gelen sayı 12 ve 11 den büyük olduğu için, 8'in yanına 11 yazılır.
> 
>           [8,11]
>16 ve 12 kıyaslayalım; 12 küçük olduğu için ilk o yazılır. 12 den sonra kendi grubunda gelen sayı 22 ve 16 dan büyük olduğu için, 12 den sonra 16 yazılır;
>
>           [8,11,12,16]
> kalan 21 ve 22 de sırasıyla eklenir;
>
>           [8,11,12,16,21,22]

- Big-O gösterimini yazınız.

>   (nlogn)
