# เรียนวิทยาการคอมพิวเตอร์ด้วยตัวเอง

หากคุณเป็นวิศวกรออนไลน์ที่เรียนรู้ด้วยตนเองหรือจบหลักสูตร Bootcamp คอร์สออนไลน์บลาๆ แล้วคุณอยากเรียนรู้การเขียนโค้ดด้วยตัวเอง โชคดีที่คุณสามารถศึกษาการเขียนโค้ด ระดับโลกได้โดยไม่ต้องเสียตังค์แม้แต่บาทเดียว โดยเป็นความรู้พื้นฐานสำหรับ ป.ตรี 💸

มีแหล่งข้อมูลมากมาย แต่บางแหล่งก็อาจจะดีกว่าที่อื่น คุณไม่จำเป็นต้องมี "200+ หลักสูตรออนไลน์ฟรี" อีกเลย แน่นอนคุณอาจจะมีคำถามเหล่านี้ในหัวหากเลือกที่จะเรียน:

*  คุณควรเรียนรู้วิชาไหนและเรียนทําไม?
*  หนังสือหรือคอร์สอันไหนดีบ้าง ?

แนวทางนี้เป็นความพยายามของเราในการตอบคําถามเหล่านี้อย่างชัดเจน

# TL;DR 

ศึกษาทั้งเก้าวิชาด้านล่างตามลําดับ โดยใช้ทั้งตําราเรียนที่หรือจะดูวิดีโอก้ได้ แต่ดูทั้งสองอย่างก็ได้นะ โดยจะศึกษา 100-200 ชั่วโมงของแต่ละหัวข้อ จากนั้นก็ลองมา list อาชีพในฝันกัน🚀


| วิชา                                          | สาเหตุที่ต้องเรียน?                                                                                                                                | หนังสือ                                               | วีดีโอ                       |
|---------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------|-----------------------------------|
| **[โปรแกรมมิ่ง](#โปรแกรมมิ่ง)**                   | อย่าเป็นคนที่ "ไม่เข้าใจ" recursion function เลย ต้อง หัดโปรแกรมมิ่ง                                                                  | [_Structure and Interpretation of Computer Programs_](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html)     | [Brian Harvey Berkeley CS 61A](https://inst.eecs.berkeley.edu/~cs61a/sp08/)|
| **[สถาปัตยกรรมคอมพิวเตอร์](#สถาปัตยกรรมคอมพิวเตอร์)**  | ถ้าคุณไม่ได้มีสมองแบบเห็นภาพแบบนามธรรม เรียนเหอะจะได้เข้าใจโครงสร้างการเขียนโปรแกรมได้ดีขึ้น           | [_Computer Systems: A Programmer's Perspective_](https://github.com/smellslikekeenspirit/an-askreddit-list-of-compsci-books/blob/master/Randal%20E.%20Bryant%2C%20David%20R.%20O%E2%80%99Hallaron%20-%20Computer%20Systems.%20A%20Programmer%E2%80%99s%20Perspective%20%5B3rd%20ed.%5D%20(2016%2C%20Pearson).pdf)|[Berkeley CS 61C](https://cs61c.org/)|
| **[โครงสร้างข้อมูลและอัลกอริทึม](#โครงสร้างข้อมูลและอัลกอริทึม)** | หากไม่ทราบวิธีใช้โครงสร้างข้อมูลที่แพร่หลาย เช่น สแต๊ก คิว โครงสร้างต้นไม้ และกราฟ คุณจะไม่สามารถแก้โจทย์ปัญหาได้เลยนะ | [_The Algorithm Design Manual_](https://www.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1849967202)                           | [Steven Skiena’s lectures](https://www3.cs.stonybrook.edu/~skiena/373/videos/)|
| **[คณิตสำหรับCS](#คณิตสำหรับCS)**                   | CS เป็นสาขาวิชาคณิตศาสตร์ประยุกต์ที่หลีกเลี่ยงไม่ได้ ดังนั้นการเรียนคณิตศาสตร์จะทำให้คุณได้เปรียบในการแข่งขัน| [_Mathematics for Computer Science_](https://courses.csail.mit.edu/6.042/spring18/mcs.pdf)                      | [Tom Leighton MIT 6.042J](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/)         |
| **[ระบบปฏิบัติการ หรือ OS](#ระบบปฏิบัติการ-หรือ-OS)**   | โค้ดส่วนใหญ่ที่คุณเขียนทำงานโดยระบบปฏิบัติการ ดังนั้นคุณควรรู้ว่าโค้ดเหล่านั้นโต้ตอบกันอย่างไร | [_Operating Systems: Three Easy Pieces_](https://pages.cs.wisc.edu/~remzi/OSTEP/)                  | [Berkeley CS 162](https://cs162.org/)                   |
| **[เน็ตเวิร์ค](#เน็ตเวิร์ค)**           | อินเทอร์เน็ตกลายเป็นเรื่องอยู่ทุกที่ในชีวิต ควรเข้าใจวิธีการทํางานเพื่อจะได้เข้าใจอินเตอร์เน็ตมากขึ้น| [_Computer Networking: A Top-Down Approach_](https://eclass.teicrete.gr/modules/document/file.php/TP326/%CE%98%CE%B5%CF%89%CF%81%CE%AF%CE%B1%20(Lectures)/Computer_Networking_A_Top-Down_Approach.pdf)              | [Stanford CS 144](https://cs144.github.io/)                   |
| **[ฐานข้อมูล](#ฐานข้อมูล)**                 | ข้อมูลเป็นหัวใจสําคัญของโปรแกรมที่สําคัญที่สุด แต่มีเพียงไม่กี่คนที่เข้าใจว่าระบบฐานข้อมูลทํางานอย่างไร | [_Readings in Database Systems_](http://www.redbook.io/)                         | [Joe Hellerstein Berkeley CS 186](http://www.infocobuild.com/education/audio-video-courses/computer-science/cs186-spring2015-berkeley.html) |
| **[ภาษาโปรแกรรมและคอมไพล์เลอร์](#ภาษาโปรแกรรมและคอมไพล์เลอร์)**       | หากคุณเข้าใจว่าภาษาและคอมไพเลอร์ทํางานอย่างไรคุณจะเขียนโค้ดที่ดีขึ้นและเรียนรู้ภาษาใหม่ได้ง่ายขึ้น | [_Crafting Interpreters_](https://craftinginterpreters.com/)           | [Alex Aiken’s course on edX](https://www.edx.org/bio/alex-aiken)   |
| **[ระบบกระจาย](#ระบบกระจาย)** | ทุกวันนี้ระบบส่วนใหญ่เป็นระบบกระจาย| [_Designing Data-Intensive Applications by Martin Kleppmann_](https://www.amazon.com/Designing-Data-Intensive-Applications-Reliable-Maintainable/dp/1449373321) | [MIT 6.824](https://pdos.csail.mit.edu/6.824/)                         |


# เยอะไปป่ะ??
หาก 9 หัวข้อเยอะไป ขอแนะนําให้โฟกัสไปที่หนังสองเล่มจะดีกว่า  จากประสบการณ์ของเราหนังสือทั้งสองเล่มนี้ให้ผลตอบแทนสูงอย่างไม่น่าเชื่อตรงเวลาโดยเฉพาะอย่างยิ่งสําหรับวิศวกรที่เรียนรู้ด้วยตนเองและเกรด bootcamp ที่ทํางานบนแอปพลิเคชันเครือข่าย พวกเขาอาจทําหน้าที่เป็น "ยาทางผ่าน" สําหรับหัวข้อและแหล่งข้อมูลอื่น ๆ ที่ระบุไว้ข้างต้น
* 📖 [Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/3e/home.html)
* 📖 [Designing Data-Intensive Applications](https://www.amazon.com/dp/B06XPJML5D/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1)

# ทําไมต้องเรียนวิทยาการคอมพิวเตอร์?
วิศวกรซอฟต์แวร์มี 2 ประเภท ได้แก่ ผู้ที่เข้าใจวิทยาการคอมพิวเตอร์ดีพอที่จะทำงานที่ท้าทายและสร้างสรรค์ และผู้ที่เพิ่งผ่านพ้นไปเพราะคุ้นเคยกับเครื่องมือระดับสูงสองสามอย่าง ทั้งคู่เรียกตัวเองว่าวิศวกรซอฟต์แวร์ และทั้งคู่มักจะได้รับเงินเดือนที่ใกล้เคียงกันในช่วงเริ่มต้นอาชีพ


วิศวกรประเภท 1 ก้าวหน้าไปสู่การทำงานที่สำเร็จลุล่วงและรายได้ที่ดีเมื่อเวลาผ่านไป ไม่ว่าจะเป็นงานเชิงพาณิชย์ที่สร้างเงินเป็นกอบเป็นกำหรือโครงการโอเพนซอร์ซที่ก้าวหน้า ความเป็นผู้นำด้านเทคนิค หรือการทำงานเป็นทีมที่มีคุณภาพสูง วิศวกรประเภทที่ 1 หาวิธีในการเรียนรู้
วิทยาการคอมพิวเตอร์ในเชิงลึก ไม่ว่าจะด้วยวิธีปกติหรือโดยการเรียนรู้อย่างไม่ลดละตลอดอาชีพการงาน

วิศวกรประเภทที่ 2 มักจะอยู่ที่ผิวเผิน เรียนรู้เครื่องมือและเทคโนโลยีเฉพาะมากกว่าที่จะเรียนรู้พื้นฐานพื้นฐาน และรับทักษะใหม่ๆ เฉพาะเมื่อกระแสของแฟชั่นทางเทคนิคเปลี่ยนแปลงไป 
ปัจจุบันจำนวนคนเข้าสู่อุตสาหกรรมเพิ่มขึ้นอย่างรวดเร็ว ในขณะที่จำนวนผู้สำเร็จการศึกษา CS ค่อนข้างคงที่ วิศวกรประเภท 2 ที่อุปทานล้นเกินนี้กำลังเริ่มลดโอกาสในการจ้างงานและทำให้พวกเขาไม่ต้องทำงานที่สำเร็จลุล่วงมากขึ้นของอุตสาหกรรม 


ไม่ว่าคุณจะมุ่งมั่นที่จะเป็นวิศวกรประเภท 1 หรือเพียงแค่มองหาความปลอดภัยในการทำงานที่มากขึ้น การเรียนรู้วิทยาการคอมพิวเตอร์เป็นหนทางเดียวที่เชื่อถือได้

## แนะนำวิชา

### โปรแกรมมิ่ง
วิทยาการคอมพิวเตอร์ใน ระดับปริญญาตรีส่วนใหญ่เริ่มต้นด้วย "บทนำ" เกี่ยวกับการเขียนโปรแกรมคอมพิวเตอร์ 
เวอร์ชันที่ดีที่สุดของหลักสูตรเหล่านี้ไม่เฉพาะสำหรับผู้เริ่มต้นเท่านั้น 
แต่ยังรวมถึงผู้ที่พลาดแนวคิดที่เป็นประโยชน์และโมเดลการเขียนโปรแกรมในขณะที่เรียนรู้การเขียนโค้ดเป็นครั้งแรก


คําแนะนํามาตรฐานของเราสําหรับเนื้อหานี้คือโครงสร้างคลาสสิกและการตีความโปรแกรมคอมพิวเตอร์ซึ่งมีให้บริการ
ออนไลน์ฟรีทั้งใน[หนังสือ](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html)และเป็น[ชุดของการบรรยายวิดีโอ MIT](http://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-001-structure-and-interpretation-of-computer-programs-spring-2005/video-lectures/)
ในขณะที่การบรรยายเหล่านั้นยอดเยี่ยมคําแนะนําวิดีโอของเราคือการบรรยาย 
[SICP ของไบรอันฮาร์วีย์](https://archive.org/details/ucberkeley-webcast-PL3E89002AA9B9879E?sort=titleSorter) (สําหรับหลักสูตร 61A ที่เบิร์กลีย์) แทน 
สิ่งเหล่านี้มีความประณีตและกําหนดเป้าหมายที่นักเรียนใหม่ได้ดีกว่าการบรรยายของ MIT


เราแนะนำให้ทำงานอย่างน้อยสามบทแรกของ SICP และท[แบบฝึกหัด](http://exercism.io/) สำหรับการฝึกปฏิบัติเพิ่มเติม ให้ลองศึกษาชุดปัญหาการเขียนโปรแกรมเล็กๆ 


ตั้งแต่คู่มือนี้ได้รับการตีพิมพ์ครั้งแรกในปี 2016 หนึ่งในคําถามที่พบบ่อยที่สุดคือตอนนี้เราแนะนําให้บันทึกการทําซ้ําล่าสุดของ 61A ที่สอนโดย John DeNero และ / หรือโปรแกรมการแต่งเพลงที่สอดคล้องกันซึ่งเป็น "ในประเพณีของ SICP" แต่ใช้ Python เราคิดว่าทรัพยากร DeNero ก็ยอดเยี่ยมเช่นกันและนักเรียนบางคนอาจเลือกพวกเขา แต่เรายังคงแนะนําการบรรยายของ SICP, Scheme และ Brian Harvey เป็นทรัพยากรชุดแรกที่พยายาม


ทำไม? เนื่องจาก SICP มีความสามารถเฉพาะตัว—อย่างน้อยก็อาจ—เพื่อเปลี่ยนความเชื่อพื้นฐานของคุณเกี่ยวกับคอมพิวเตอร์และการเขียนโปรแกรม ไม่ใช่ทุกคนจะได้รับประสบการณ์นี้ บางคนจะเกลียดหนังสือเล่มนี้ บางคนจะไม่ผ่านหน้าแรกๆ แต่ผลตอบแทนที่เป็นไปได้นั้นคุ้มค่าที่จะลอง


หากคุณไม่ชอบ SICP ให้ลองเขียนโปรแกรม หากยังไม่เหมาะ ลองใช้ [How to Design Programs](http://www.htdp.org/) หากสิ่งเหล่านี้ไม่คุ้มค่าสำหรับความพยายามของคุณ อาจเป็นสัญญาณว่าคุณควรมุ่งเน้นไปที่หัวข้ออื่นเป็นระยะเวลาหนึ่ง และทบทวนระเบียบวินัยของการเขียนโปรแกรมในอีกหนึ่งปีหรือสองปี

สุดท้ายนี้ ขอชี้แจง: คู่มือนี้ไม่ได้ออกแบบมาสำหรับผู้ที่ยังใหม่ต่อการเขียนโปรแกรม เราคิดว่าคุณเป็นโปรแกรมเมอร์ที่มีความสามารถและไม่มีพื้นฐานด้านวิทยาการคอมพิวเตอร์และต้องการเติมเต็มช่องว่างความรู้ ข้อเท็จจริงที่ว่าเราได้รวมหัวข้อ "การเขียนโปรแกรม" ไว้เป็นเพียงเครื่องเตือนใจว่าอาจมีอีกมากที่ต้องเรียนรู้ สำหรับผู้ที่ไม่เคยเขียนโค้ดมาก่อน แต่ต้องการ คุณอาจต้องการคำแนะนำ[แบบนี้](https://www.reddit.com/r/learnprogramming/wiki/faq#wiki_getting_started)


[![Structure and Interpretation of Computer Programs](https://teachyourselfcs.com/sicp.jpg)](https://mitpress.mit.edu/sites/default/files/sicp/full-text/book/book.html) 

### สถาปัตยกรรมคอมพิวเตอร์

สถาปัตยกรรมคอมพิวเตอร์—บางครั้งเรียกว่า “ระบบคอมพิวเตอร์” หรือ “องค์กรคอมพิวเตอร์”—เป็นสิ่งแรกที่สำคัญในการพิจารณาด้านคอมพิวเตอร์ภายใต้พื้นผิวของซอฟต์แวร์ จากประสบการณ์ของเรา มันเป็นพื้นที่ที่ถูกละเลยมากที่สุดในหมู่วิศวกรซอฟต์แวร์ที่เรียนรู้ด้วยตนเอง


หนังสือแนะนำตัวที่เราชื่นชอบคือ [Computer Systems: A Programmer's Perspective](http://csapp.cs.cmu.edu/3e/home.html) และ[หลักสูตรสถาปัตยกรรมคอมพิวเตอร์เบื้องต้น](http://csapp.cs.cmu.edu/3e/courses.html)ทั่วไปที่ใช้หนังสือเล่มนี้จะครอบคลุมส่วนใหญ่ของบทที่ 1-6


เรารัก CS:APP สำหรับแนวทางเชิงโปรแกรมเมอร์เชิงปฏิบัติ แม้ว่าสถาปัตยกรรมคอมพิวเตอร์จะมีอะไรมากกว่าที่ครอบคลุมในหนังสือ แต่ก็เป็นจุดเริ่มต้นที่ดีสำหรับผู้ที่ต้องการเข้าใจระบบคอมพิวเตอร์เป็นหลัก เพื่อที่จะเขียนซอฟต์แวร์ได้เร็ว มีประสิทธิภาพมากขึ้น และเชื่อถือได้มากขึ้น


สำหรับผู้ที่ต้องการทั้งการแนะนำหัวข้อที่นุ่มนวลกว่าและความสมดุลของข้อกังวลด้านฮาร์ดแวร์และซอฟต์แวร์ เราขอแนะนำ The Elements of Computing Systems หรือที่เรียกว่า “Nand2Tetris” นี่คือหนังสือที่มีความทะเยอทะยานที่พยายามทำให้คุณเข้าใจอย่างแน่วแน่ว่าทุกอย่างในคอมพิวเตอร์ทำงานอย่างไร แต่ละบทเกี่ยวข้องกับการสร้างส่วนเล็กๆ ของระบบโดยรวม ตั้งแต่การเขียนลอจิกเกทเบื้องต้นใน HDL ผ่าน CPU และแอสเซมเบลอร์ ไปจนถึงแอพพลิเคชั่นขนาดเท่าเกม Tetris

เราแนะนำให้อ่านหกบทแรกของหนังสือเล่มนี้และดำเนินโครงการที่เกี่ยวข้องให้เสร็จ สิ่งนี้จะช่วยพัฒนาความเข้าใจของคุณเกี่ยวกับความสัมพันธ์ระหว่างสถาปัตยกรรมของเครื่องและซอฟต์แวร์ที่ทำงานบนเครื่อง

ครึ่งแรกของหนังสือ (และโครงการทั้งหมด) มีให้บริการฟรีจากเว็บไซต์ [and2Tetris](http://www.nand2tetris.org/) นอกจากนี้ยังมีหลักสูตร [Coursera](https://www.coursera.org/learn/build-a-computer) พร้อมวิดีโอประกอบ


ในการแสวงหาความเรียบง่ายและความเหนียวแน่น Nand2Tetris แลกเปลี่ยนความลึก โดยเฉพาะอย่างยิ่ง สองแนวคิดที่สำคัญมากในสถาปัตยกรรมคอมพิวเตอร์สมัยใหม่คือPipeliningและลำดับชั้นของหน่วยความจำ แต่ทั้งสองส่วนใหญ่ไม่มีอยู่ในบทความนี้


เมื่อคุณรู้สึกสบายใจกับเนื้อหาของ Nand2Tetris เราแนะนำให้กลับไปที่ CS:APP หรือ[Computer Organization and Design](https://smile.amazon.com/Computer-Organization-Design-Fifth-Architecture/dp/0124077269) Patterson และ Hennessy ซึ่งเป็นข้อความที่ยอดเยี่ยมและตอนนี้คลาสสิก ไม่ใช่ทุกส่วนในหนังสือที่มีความสำคัญ เราขอแนะนำให้ทำตามหลักสูตร [CS61C](http://inst.eecs.berkeley.edu/~cs61c/sp15/) ของ Berkeley "แนวคิดที่ยอดเยี่ยมในสถาปัตยกรรมคอมพิวเตอร์" สำหรับการอ่านที่เฉพาะเจาะจง บันทึกการบรรยายและห้องทดลองมีให้บริการทางออนไลน์ และการบรรยายที่ผ่านมาจะอยู่ใน Internet Archive

[![Computer Systems: A Programmer's Perspective](https://teachyourselfcs.com/csapp.jpg)](http://csapp.cs.cmu.edu/3e/home.html)

> ฮาร์ดแวร์คือแพลตฟอร์ม

*-- Mike Acton, Engine Director presso Insomniac Games\
([watch his CppCon talk](https://www.youtube.com/watch?v=rX0ItVEVjHc))*

### โครงสร้างข้อมูลและอัลกอริทึม

เราเห็นด้วยกับภูมิปัญญาทั่วไปหลายทศวรรษที่ความคุ้นเคยกับอัลกอริธึมทั่วไปและโครงสร้างข้อมูลเป็นหนึ่งในแง่มุมที่ส่งเสริมการศึกษาด้านวิทยาการคอมพิวเตอร์มากที่สุด นอกจากนี้ยังเป็นสถานที่ที่ดีเยี่ยมในการฝึกอบรมความสามารถในการแก้ปัญหาทั่วไป ซึ่งจะเป็นประโยชน์ต่อการศึกษาด้านอื่นๆ ทุกด้าน


มีหนังสือหลายร้อยเล่ม แต่หนังสือที่เราชอบที่สุดคือ [The Algorithm Design Manual](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) โดย Steven Skiena เขาชอบการแก้ปัญหาอัลกอริธึมอย่างชัดเจน และมักจะประสบความสำเร็จในการส่งเสริมความกระตือรือร้นที่คล้ายคลึงกันในหมู่นักเรียนและผู้อ่านของเขา ในความเห็นของเรา ข้อความแนะนำสองฉบับ (CLRS และ Sedgewick) มีแนวโน้มที่จะพิสูจน์ได้ยากเกินไปสำหรับผู้ที่เรียนรู้เนื้อหาในเบื้องต้นเพื่อช่วยในการแก้ปัญหาในทางปฏิบัติ


สำหรับผู้ที่ชื่นชอบการบรรยายผ่านวิดีโอ [Skiena](https://www3.cs.stonybrook.edu/~skiena/373/videos/) นำเสนอออนไลน์ของเขาอย่างไม่เห็นแก่ตัว เราชอบหลักสูตรของ Tim Roughgarden เช่นกัน ซึ่งมีอยู่ใน [Coursera](https://www.coursera.org/specializations/algorithms) และ[ที่อื่นๆ](http://timroughgarden.org/videos.html) ไม่ว่าคุณจะชอบสไตล์การบรรยายของ Skiena หรือ Roughgarden จะเป็นเรื่องของความชอบส่วนตัว อันที่จริง มีทางเลือกดีๆ มากมายให้เลือก ดังนั้นหากคุณพบตัวเลือกอื่นที่คุณชอบ เราขอแนะนำให้คุณใช้ตัวเลือกนี้ต่อไป!

สำหรับการฝึกฝน แนวทางที่เราต้องการคือให้นักเรียนแก้ปัญหาใน [Leetcode](https://leetcode.com/) สิ่งเหล่านี้มักจะเป็นปัญหาที่น่าสนใจพร้อมแนวทางแก้ไขและการอภิปรายที่เหมาะสม นอกจากนี้ยังช่วยให้คุณทดสอบความคืบหน้ากับคำถามที่มักใช้ในการสัมภาษณ์ทางเทคนิคที่บริษัทซอฟต์แวร์ที่มีการแข่งขันสูง เราขอแนะนำให้แก้ปัญหาแบบสุ่ม leetcode ประมาณ 100 รายการซึ่งเป็นส่วนหนึ่งของการศึกษาของคุณ


สุดท้ายนี้ เราขอแนะนำ [How to Solve It](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/) เป็นแนวทางที่ยอดเยี่ยมและไม่ซ้ำใครในการแก้ปัญหาทั่วไป มันใช้ได้กับวิทยาการคอมพิวเตอร์เช่นเดียวกับคณิตศาสตร์


[![The Algorithm Design Manual](https://teachyourselfcs.com/skiena.jpg)](https://smile.amazon.com/Algorithm-Design-Manual-Steven-Skiena/dp/1848000693/) [![How to Solve It](https://teachyourselfcs.com/polya.jpg)](https://smile.amazon.com/How-Solve-Mathematical-Princeton-Science/dp/069116407X/)

> ฉันมีวิธีการเดียวที่ฉันแนะนำอย่างกว้างขวาง นั่นคือ คิดก่อนเขียน

*— Richard Hamming*

###  คณิตสำหรับCS

ในบางแง่ วิทยาการคอมพิวเตอร์เป็นสาขาหนึ่งของคณิตศาสตร์ประยุกต์ที่รก ในขณะที่วิศวกรซอฟต์แวร์หลายคนพยายาม—และประสบความสำเร็จในระดับต่างๆ—โดยไม่สนใจสิ่งนี้ เราขอแนะนำให้คุณยอมรับมันด้วยการศึกษาโดยตรง การทำเช่นนั้นได้สำเร็จจะทำให้คุณได้เปรียบในการแข่งขันอย่างมหาศาลมากกว่าผู้ที่ไม่..

สาขาวิชาคณิตศาสตร์ที่มีความเกี่ยวข้องมากที่สุดสำหรับ CS นั้นเรียกอย่างกว้าง ๆ ว่า "คณิตศาสตร์แบบไม่ต่อเนื่อง" โดยที่ "ไม่ต่อเนื่อง" ตรงข้ามกับ "แบบต่อเนื่อง" และเป็นกลุ่มของหัวข้อคณิตศาสตร์ประยุกต์ที่น่าสนใจนอกแคลคูลัส ด้วยคำจำกัดความที่คลุมเครือ การพยายามครอบคลุม "คณิตศาสตร์แบบไม่ต่อเนื่อง" จึงไม่มีความหมาย เป้าหมายที่สมจริงยิ่งขึ้นคือการสร้างความเข้าใจในการทำงานของลอจิก คอมบินาโตริก และความน่าจะเป็น ทฤษฎีเซต ทฤษฎีกราฟ และทฤษฎีจำนวนเล็กน้อยที่ให้ข้อมูลการเข้ารหัส พีชคณิตเชิงเส้นเป็นพื้นที่ที่คุ้มค่าสำหรับการศึกษาเพิ่มเติม เนื่องจากมีความสำคัญในคอมพิวเตอร์กราฟิกและการเรียนรู้ของเครื่อง


จุดเริ่มต้นที่เราแนะนำสำหรับคณิตศาสตร์แบบไม่ต่อเนื่องคือชุดบันทึกการบรรยายโดย [László Lovász ศาสตราจารย์ Lovász](https://cims.nyu.edu/~regev/teaching/discrete_math_fall_2005/dmbook.pdf) ทำได้ดีมากในการทำให้เนื้อหาเข้าถึงได้ง่ายและเข้าใจง่าย ดังนั้นสิ่งนี้จึงเป็นจุดเริ่มต้นที่ดีกว่าข้อความที่เป็นทางการ

สำหรับการรักษาขั้นสูง เราขอแนะนำ [Mathematics for Computer Science](https://courses.csail.mit.edu/6.042/spring17/mcs.pdf) ซึ่งเป็นบันทึกบรรยายความยาวเป็นหนังสือสำหรับหลักสูตร MIT ที่มีชื่อเดียวกัน วิดีโอบรรยายของหลักสูตรนั้นยังมีให้ใช้งานฟรี และเป็น[วิดีโอบรรยาย](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-fall-2010/video-lectures/)ที่เราแนะนำสำหรับวิชาคณิตศาสตร์แบบไม่ต่อเนื่อง

สําหรับพีชคณิตเชิงเส้นเราขอแนะนําให้เริ่มต้นด้วย[สาระสําคัญของชุดวิดีโอพีชคณิตเชิงเส้น](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)ตามด้วยการบรรยาย[หนังสือ](https://www.amazon.com/Introduction-Linear-Algebra-Gilbert-Strang/dp/0980232775/)และ[วิดีโอ](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/video-lectures/)ของกิลเบิร์ตสแตรง

> หากผู้คนไม่เชื่อว่าคณิตศาสตร์นั้นง่าย เพราะพวกเขาไม่รู้ว่าชีวิตที่ซับซ้อนเป็นอย่างไร
*— John von Neumann*

### ระบบปฏิบัติการ หรือ OS

[แนวคิดระบบปฏิบัติการ](https://www.amazon.com/dp/1118063333/) ("หนังสือไดโนเสาร์") และ[ระบบปฏิบัติการสมัยใหม่](https://www.amazon.com/dp/013359162X/)เป็นหนังสือ "คลาสสิก" เกี่ยวกับระบบปฏิบัติการ ทั้งสองได้รับการวิพากษ์วิจารณ์เนื่องจากขาดความชัดเจนและความไม่เป็นมิตรของนักเรียนทั่วไป

ระบบปฏิบัติการ: Three Easy Pieces เป็นทางเลือกที่ดีที่ออนไลน์ได้อย่างอิสระ โดยเฉพาะอย่างยิ่งเราชอบโครงสร้างและการอ่านของหนังสือและรู้สึกว่าการออกกําลังกายนั้นคุ้มค่า

หลังจาก OSTEP เราขอแนะนําให้คุณสํารวจการตัดสินใจออกแบบระบบปฏิบัติการเฉพาะผ่านหนังสือสไตล์ "{OS} Internals" เช่นความเห็นของ [Lion's commentary on Unix](https://www.amazon.com/Lions-Commentary-Unix-John/dp/1573980137/) , [The Design and Implementation of the FreeBSD Operating System](https://www.amazon.com/Design-Implementation-FreeBSD-Operating-System/dp/0321968972/) และ [Mac OsX](https://www.amazon.com/Mac-OS-Internals-Systems-Approach/dp/0321278542/)เราขอแนะนํา [Linux Kernel Development](https://www.amazon.com/Linux-Kernel-Development-Robert-Love/dp/0672329468) ที่ยอดเยี่ยมของโรเบิร์ตเลิฟ

วิธีที่ยอดเยี่ยมในการรวมความเข้าใจเกี่ยวกับระบบปฏิบัติการของคุณคือการอ่านโค้ดของเคอร์เนลขนาดเล็กและเพิ่มคุณสมบัติ ทางเลือกหนึ่งคือ [xv6](https://pdos.csail.mit.edu/6.828/2016/xv6.html) ซึ่งเป็นพอร์ตของ Unix V6 ถึง ANSI C และ x86 ได้รับการดูแลสำหรับหลักสูตรที่ MIT OSTEP มีภาคผนวกของ [xv6 lab](http://pages.cs.wisc.edu/~remzi/OSTEP/lab-projects-xv6.pdf) ที่มีศักยภาพซึ่งเต็มไปด้วยแนวคิดที่ยอดเยี่ยมสำหรับโครงการที่มีศักยภาพ

[![Operating Systems: Three Easy Pieces](https://teachyourselfcs.com/ostep.jpeg)](http://pages.cs.wisc.edu/~remzi/OSTEP/)


### เน็ตเวิร์ค

มีคนเคยกล่าวว่าวิศวกรรมซอฟต์แวร์จํานวนมากอยู่บนเว็บเซิร์ฟเวอร์และลูกค้าหนึ่งในพื้นที่ที่มีค่าที่สุดของวิทยาการคอมพิวเตอร์คือระบบเครือข่ายคอมพิวเตอร์ นักเรียนที่เรียนรู้ด้วยตนเองของเราที่ศึกษาเครือข่ายอย่างเป็นระบบพบว่าในที่สุดพวกเขาก็เข้าใจคําศัพท์แนวคิดและโปรโตคอลที่พวกเขาถูกล้อมรอบด้วยมานานหลายปี 

หนังสือเล่มโปรดของเราในหัวข้อนี้คือ [Computer Networking: A Top-Down Approach](https://smile.amazon.com/Computer-Networking-Top-Down-Approach-7th/dp/0133594149/) โครงการเล็กๆ และแบบฝึกหัดในหนังสือนั้นคุ้มค่าที่จะทำ และโดยเฉพาะอย่างยิ่งเราชอบ ["ห้องปฏิบัติการ Wireshark"](http://www-net.cs.umass.edu/wireshark-labs/) ซึ่งพวกเขาได้จัดเตรียมไว้ให้ทางออนไลน์



