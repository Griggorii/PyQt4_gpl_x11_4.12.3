# PyQt4_gpl_x11_4.12.3 Ubuntu 20.04 QtOpenGL generated by MetaSIP
PyQt4 GPL X11 4.12.3 patch to QT4.8.7 QtDesigner fix crash ubuntu 20.04 bootstrap module in mainframe update qmake make dump update parameters

                               Ubuntu support 16.04/16.10/17.04/17.10/18.04/18.10/19.04/19.10/20.04
                               
Install full QT4.8.7 onli ubuntu 20.04 <- version! install https://github.com/Griggorii/Ubuntu_20.04_QT4.8.7 Only for version 20.04 do not install on other versions of distributions will not work!

&& sudo tar xvpf PyQt4_gpl_x11-4.12.3.tar.xz -C /

&& cd /home/griggorii/PyQt4_gpl_x11_4.12.3-master/PyQt4_gpl_x11-4.12.3

&& sudo make install

&& cd ~/

_____________________________________________________________________________________________


 /usr/bin/sip                                                                                 


                                                           Griggorii@gmail.com

История поисковиков до сих пор молчит о том кто собрал первый дистрибутив в мире я же не доказываю , а ставлю перед фактом что все идет к тому как я собирал его ранее на 16.04 ищут связанную ошибку об отсутствии /usr/bin/sip для QT4 и QT5 на данный момент я подготовил это для ubuntu 20.04 , но вы можете сделать и для более нового дистрибутива

Inpack arhive sip-4.19.12.tar.gz

Ubuntu copy folder sip-4.19.12 /tmp

&& cd /tmp/sip-4.19.12

&& sudo apt install libpython3.8-dev

&& python3 configure.py

&& make

&& sudo make install

_____________________________________________________________________________________

                                                            Update QT sip

 /usr/bin/sip                                         

Update QT sip

PyQt4_gpl_x11-4.12.3 Rebuild pocess new update python3 https://github.com/Griggorii/PyQt4_gpl_x11_4.12.3

&& sudo tar xvpf PyQt4_gpl_x11-4.12.3.tar.xz -C /

&& cd /home/griggorii/PyQt4_gpl_x11_4.12.3-master/PyQt4_gpl_x11-4.12.3

&& sudo make clean

&& sudo rm ./Makefile

&& sudo python3 configure.py

accept the terms of the license copy yes to enter next generate new makefile

example Do you accept the terms of the license? yes

&& sudo make -j4 && sudo make -i install

&& cd ~/

&& sudo rm -rf /home/griggorii

Впрочем эти поиски и вопросы на спец форумах о поиске этого решения говорит о том что идет эмуляция и симуляция сборочного процесса , а компании нанимают всяких кью инженеров лишь бы отмыть деньги , а не заплатить реальному самоучке и даже создателю собственного архитектурного решения дистрибутива , а когда приходят люди и начинают болтать про ментеини нам бесплатно пол системы это все бесплатное , но тем не менее компании нанимают сборщиков инженеров за деньги то хочется сказать словами генадия зюганова: вы еду тоже бесплатно едите или она вам с неба на тарелочку в горошек падает?

