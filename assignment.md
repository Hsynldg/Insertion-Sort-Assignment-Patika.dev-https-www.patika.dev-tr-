1.Insertion sorta göre aşamalar:
[ 22 27 16 2 18 6]
[ 22 16 27 2 18 6]
[ 16 22 27 2 18 6]
[ 16 22 2 27 18 6]
[ 16 2 22 27 18 6]
[ 2 16 22 27 18 6]
[ 2 16 22 18 27 6]
[ 2 16 18 22 27 6]
[ 2 16 18 22 6 27]
[ 2 16 18 6 22 27]
[ 2 16 6 18 22 27]
[ 2 6 16 18 22 27]

2.Insertion sort Big-O gösterimi:
        Best Case senaryoda n kez iterasyon yaparız ve dizideki elemanların hepsi yerli yerindedir bundan dolayı hiç kaydırma yapmayız. Best case senaryoda O(n)*1'den O(n)'dir.

        Worst Case senaryoda n kez iterasyon yaparız ve hepsini yer değiştirmek zorunda kalacağımızı varsayırız bu da n kez yer değiştirme manasına gelir.Worst case senaryoda O(n)*O(n)=O(n^2) olur.

3.Diziyi sıraladıktan sonra 18 dizinin ortasında kaldığı için Average Case senaryo olur.

4.[7 3 5 8 2 9 4 15 16] dizisinin insertion sorta göre ilk 4 aşaması:
    [3 7 5 8 2 9 4 15 16]
    [3 5 7 8 2 9 4 15 16]
    [3 5 7 2 8 9 4 15 16]
    [3 5 2 7 8 9 4 15 16]

