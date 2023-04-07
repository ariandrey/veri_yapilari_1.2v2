İkili Ağaç Düzey Sırası Geçişi

İkili ağaç düzey sırası geçişi, ikili ağacın düğümlerinin seviye sırasına göre geçmesi işlemidir. Bu işlem ağacın kökünden başlayarak seviye seviye aşağıya doğru ilerler ve her seviyedeki düğümleri soldan sağa doğru tarar *(soldan sağa, seviye seviye)* . Yani önce ağacın kökü, sonra kökün sol alt düğümü, ardından kökün sağ alt düğümü ve böyle devam ederek tüm düğümler seviye sırasına göre taranır.

Bu işlem genellikle genişlik öncelikli arama algoritması (BFS) ile gerçekleştirilir. BFS algoritması, ağacın her bir seviyesini sırayla tarayarak düğümleri ziyaret eder ve bu sayede düğümlerin seviye sırasına göre geçişi sağlanır. by www.mshowto.org

İkili ağaç düzey sırası geçişi, ağacın yapısının ve düğümlerinin değerlerinin görsel olarak daha rahat anlaşılmasına yardımcı olur. Ayrıca, ağaçtaki düğümlerin seviye sırasına göre geçişini sağlayarak, ağaçtaki verilerin işlenmesi veya arama işlemleri gibi bazı işlemlerin daha verimli bir şekilde yapılmasını sağlar.

İkili ağaç düzey sırası geçişi şu şekilde olur:
    1          Seviye 1: 1 
   / \         Seviye 2: 2 3
  2   3        Seviye 3: 4 5 6
 / \   \
4   5   6
*Bu şekilde ağacın tüm düğümleri soldan sağa, seviye seviye taranmış olur.*

Not;
1->BFS çalışma mantığı;

Bir başlangıç düğümü belirlenir ve tüm komşular ziyaret edilir. DFS’ den farklı olarak BFS’ de ziyaret edilen komşunun aynı anda gidilebilecek tüm komşuları aynı anda kuyruğa eklenir. DFS’ de hatırlayacağınız üzere bir komşudan sadece gidilebilecek bir diğer komşuya gidiliyor ve yığına ekleniyordu.
