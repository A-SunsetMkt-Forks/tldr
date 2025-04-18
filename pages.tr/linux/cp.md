# cp

> Dosya ve dizinleri kopyala.
> Daha fazla bilgi için: <https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html>.

- Bir dosyayı başka bir konuma kopyala:

`cp {{örnek/yol/kaynak_dosya.ext}} {{örnek/yol/hedef_dosya.ext}}`

- Bir dosyayı ismini değiştirmeden başka bir dizine kopyala:

`cp {{örnek/yol/kaynak_dosya.ext}} {{örnek/yol/hedef_ana_dizin}}`

- Bir dizinin içeriğini başka bir konuma tekrarlı şekilde kopyala (eğer belirtilen konum varsa dizin onun içine kopyalanır):

`cp {{[-r|--recursive]}} {{örnek/yol/kaynak_dizin}} {{örnek/yol/hedef_dizin}}`

- Bir dizini tekrarlı şekilde ayrıntılı modda kopyala (dosyaları kopyalandıkları gibi gösterir):

`cp {{[-vr|--verbose --recursive]}} {{örnek/yol/kaynak_dizin}} {{örnek/yol/hedef_dizin}}`

- Metin dosyalarını interaktif modda başka bir konuma kopyala (üstüne yazmadan önce kullanıcıyı bilgilendirir):

`cp {{[-i|--interactive]}} {{*.txt}} {{örnek/yol/hedef_dizin}}`

- Kopyalamadan önce sembolik linkleri izle:

`cp {{[-L|--dereference]}} {{link}} {{örnek/yol/hedef_dizin}}`

- Kopyalarken kaynak dosyalarının tam konumunu belirt:

`cp --parents {{kaynak/örnek/yol/dosya}} {{örnek/yol/hedef_dosya}}`
