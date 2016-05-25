# Open Source Project Policy

The concept known as open source, in which people try to accelerate development by making it so that developers from around the world can participate and not limiting things to a particular organization, has had its effectiveness verified and taken root in software, and that wave is currently heading towards hardware. However, compared to making software open source, in hardware there are many elements that must be considered. First, for hardware, adding to software, there are many cases where the intellectual property to be released (plans, CG/3D data, pictures, visuals, etc) spans a broad range. Moreover, product liability must also be considered.

Product liability laws are enacted in accordance with the world view of protecting consumers that are originally in a “weak” position from manufacturers that are in a “strong” position. However, due to the popularization of digital fabrication, it is now becoming so that individuals are able to do said manufacturing, and there is the possibility that product liability will be applicable to individuals as well. By making something open source, one can expect it to spread, but on the other hand, by releasing it to the public, one must think of the risks related to product liability. In such a situation, there are concerns that people may hesitate to release something to the public.

Therefore, under the editorial supervision of a lawyer, I have created a terms of use for projects that will release hardware and software via open source to the public, as well as an FAQ that demonstrates its interpretation through specific examples. I am releasing it as template here in the hopes that by having intellectual property rights and product liability be treated appropriately, it will accelerate challenges towards innovative creation in future open source projects.

Furthermore, these terms of use were created at the Institute of Advanced Media Arts and Sciences [IAMAS] as part of the “[Center of Kansei-oriented Digital Fabrication](http://coi.sfc.keio.ac.jp/)” which was selected by the “Creative Innovation Creation Program (Center of Innovation COI STREAM)” as run by the Ministry of Education, Culture, Sports, Science and Technology (MEXT) and the Japan Science and Technology Agency (JST).

**Disclaimers:**  
This document is aimed towards accumulating and sharing the trials-and-errors and know-how in open source hardware projects. The author and copyright holder shall assume no liability for any damages that may be incurred by users or third parties due to the usage of the information posted in this document. This also applies to the event that there is an error in the posted content.

The “Open Source Project Policy” is provided through an [‘Attribution-ShareAlike 4.0 International’ Creative Commons License](http://creativecommons.org/licenses/by-sa/4.0/deed). Furthermore, following Section 8.c of said license, I explicitly waive the conditions and rights related to ‘Attribution’ as stipulated in Section 3.a of the same license. Therefore, persons that will create derivatives of this terms of use will be able to utilize this terms of use without having to conduct an attribution to the copyright owners name as called for in this license.

In the event that the terms of use will be used in several projects, please change the terms of service to match each project, and release the results under the same license. Also, for the purpose of reuse or reproduction, whenever possible, please fork the project on GitHub, making the relationship of derivation clear.

Creation: Shigeru Kobayashi ([Institute of Advanced Media Arts and Sciences [IAMAS]](http://www.iamas.ac.jp/en/))  
Translation (READ ME and FAQ): Matthew Drew ([Institute of Advanced Media Arts and Sciences [IAMAS]](http://www.iamas.ac.jp/en/))  
Editorial Supervision: Lawyer, Tasuku Mizuno ([City Lights Law Office](http://citylights-lawoffice.tumblr.com/))

---

# オープンソース・プロジェクト・ポリシー

特定の組織に限定せず世界中から開発者が参加できるようにすることで開発を加速しようというオープンソースの考え方は、ソフトウェアにおいてその有効性が証明されて定着し、その波はハードウェアに向かおうとしています。しかしながら、ハードウェアの場合には、ソフトウェアをオープンソースにする場合と比較して、配慮しなければならない要素が多くなります。まず、ハードウェアの場合には、ソフトウェアの場合に加え、図面、CG・3Dデータ、写真、映像など公開の対象となる知的財産も多岐に渡るケースが多くなります。加えて、製造物責任に対しても配慮しなければなりません。

製造物責任法は、もともと「弱い」立場にある消費者を「強い」立場にある製造業者から守る、という世界観にもとづいて制定されたものです。しかしながら、デジタルファブリケーションの普及によって個人でも製造できるようになりつつある現在、製造物責任は個人に対しても適用される可能性があります。オープンソースにすることで広がりが期待できる反面で、公開することによって発生する製造物責任に関するリスクを考えなければならない状況においては、公開を躊躇してしまうことも懸念されます。

そこで、ハードウェアやソフトウェアをオープンソースで公開するプロジェクトのための利用規約、およびその解釈を具体例で示したFAQを、法律の専門家である弁護士の監修のもと作成しました。今後のオープンソースプロジェクトにおいて、知的財産権や製造物責任が適切に扱われることによってイノベーション創出への挑戦が加速されることを期待して、ここにテンプレートとして公開いたします。

なお、この利用規約は、文部科学省・科学技術振興機構による「革新的イノベーション創出プログラム（センター・オブ・イノベーションCOI STREAM）」に採択された「[感性とデジタル製造を直結し、生活者の創造性を拡張するファブ地球社会創造拠点](http://coi.sfc.keio.ac.jp/)」の一環として、連携機関の1つである情報科学芸術大学院大学［IAMAS］において作成されました。

**免責事項：**  
このドキュメントは、オープンソースハードウェアのプロジェクトにおける試行錯誤やノウハウを蓄積および共有することを目的としています。著者および著作権者は、このドキュメントに掲載した情報の利用によって、利用者または第三者等に何らかの損害が発生したとしても、かかる損害については一切の責任を負うものではありません。掲載内容に誤りがあった場合も同様です。

『Open Source Project Policy』は[クリエイティブ・コモンズ・ライセンス【表示-継承 4.0 国際】](http://creativecommons.org/licenses/by-sa/4.0/deed.ja)で提供されています。なお、本ライセンス8.c.の規定にしたがい、本ライセンス3.a.に規定する【表示】に関する条件または権利を明示的に放棄いたします。したがいまして、本利用規約の派生物をつくる方は、本ライセンスが求める権利者名の表示を行わないでも、本利用規約を利用することができます。

それぞれのプロジェクトで使用する場合には、それぞれのプロジェクトに合わせて改変し、その結果を同じライセンスの元で公開してください。また、二次利用の際には可能なかぎりGitHub上でforkし、派生関係がわかるようにしてください。

作成：小林 茂（[情報科学芸術大学院大学［IAMAS］](http://www.iamas.ac.jp/)）  
翻訳（READ MEおよびFAQ）：Matthew Drew（[情報科学芸術大学院大学［IAMAS］](http://www.iamas.ac.jp/)）  
監修：弁護士 水野祐（[シティライツ法律事務所](http://citylights-lawoffice.tumblr.com/)）