## intent:greet
- hey
- hei
- Salut
- salut
- bună
- salutare
- hello
- bună ziua
- hei!
- hi

## intent:goodbye
- bye
- pa
- paa
- paaa
- pa pa
- papa
- mersi
- merci
- mulțumesc
- gata
- super

## intent:affirm
- da
- daa
- da da
- dada
- dap
- sigur
- ok
- yep
- yes

## intent:store_request
- Vreau să reții ceva
- Poți să reții ceva, te rog?
- Memorează
- Memorează ceva
- Reține ceva
- Ține minte
- Memo
- reține

## intent:store_location
- cartea e [pe](prep) masă
- Cardul de debit este [în](prep) portofelul vechi
- buletinul meu se află [în](prep) rucsac
- biblioteca se află [la](prep) etajul 5
- service-ul gsm este [pe](prep) strada Ecaterina Teodoroiu numărul 12
- Am pus foile cu tema la mate [pe](prep) dulapul din sufragerie
- Alex stă [în](prep) căminul P5
- Maria Popescu locuiește [pe](prep) Bulevardul Timișoara numărul 5
- Daniela stă la blocul 23
- eu stau la adresa str. Ec. Teod. nr. 17
- Bonurile de transport sunt în plicul de pe raft
- cardul de memorie e [sub](prep) cutia telefonului
- tastatura mea este [în](prep) depozit
- profesorul se află [în](prep) camera vecină
- am lăsat lădița cu cartofi [în](prep) pivniță
- mi-am pus casca de înot [în](prep) dulapul cu tricouri
- geaca de iarnă este [în](prep) șifonierul de acasă
- lămpile solare sunt [de la](prep) bricostore
- perechea de adidași albi este [de la](prep) intersport din Afi
- Alin Dumitru stă în Militari Residence
- am lăsat suportul de brad la țară în garaj
- pachetul de creioane colorate este pe polița de pe perete
- mi-am așezat prosoapele pe suport
- am cumpărat florile [de la](prep) mireille
- am luat veioza [de la](prep) București
- sandalele sunt de la magazinul benvenutti
- trandafirii sunt [de la](prep) Nicu
- chitara mea este de la Andrei
- am mers cu mașina până la Iași
- telefonul lui Jan este [pe](prep) noptieră
- tricoul meu de alergat e în șifonier pe hol
- trusa de machiaj a Anisiei este în geamantanul verde
- ganterele lui Horia sunt sub canapea
- bormașina cu percuție a lui Vlad e [la](prep) Timișoara
- pungile acestea sunt de la mall
- Bob se află [pe](prep) stația spațială
- Clara a venit [de pe](prep) muntele Olimp
- Rodica se întoarce [de la](prep) festivalul Untold

## intent:get_location
- [Unde](query_word_loc) se află ochelarii
- [Unde](query_word_loc) e buletinul?
- știi [unde](query_word_loc) am pus cheile
- poți să-mi zici [unde](query_word_loc) este încârcătorul de telefon
- zi-mi unde am pus ochelarii de înot
- [unde](query_word_loc) am lăsat ceasul?
- [pe unde](query_word_loc) e sticla de ulei
- pe unde mi-am pus pantofii negri
- [de unde](query_word_loc) am cumpărat uscătorul de păr
- de unde au venit cartofii în Europa
- de unde pleacă trenul IR1892
- [până unde](query_word_loc) a alergat aseară Marius?
- până unde au ajuns radiațiile de la Cernobâl
- de unde am luat draperiile din sufragerie?

## intent:store_following_attr
- mailul lui Alex [este](a_fi) următorul
- valoarea constantei pi [este](a_fi) următoarea
- colegii care au luat 10 la ML [sunt](a_fi) următorii:
- materiile opționale din anul 1 [sunt](a_fi) următoarele
- tehnologiile folosite de aplicație sunt următoarele
- codul de acces [este](a_fi) ăsta
- numărul de la casă al Mariei [e](a_fi) acesta
- dimensiunile portbagajului meu de la mașină [sunt](a_fi) acestea
- adresa mea de la București [e](a_fi) aceasta
- versiunile de Windows 10 [sunt](a_fi) acestea
- lunile pe care am decontat abonamentul sunt cele care urmează
- ecuația fluxului electromagnetic [e](a_fi) cea care urmează
- colegii mei de liceu [erau](a_fi) cei ce urmează
- dioptriile mele de la ochelari [erau](a_fi) ultima dată cele ce urmează

## intent:store_attr
- Mailul lui [Alex](person) Marin [este](a_fi) alex@marin.com
- Adresa [Elenei](owner) [este](a_fi) strada Zorilor numărul 9
- Numărul de telefon al lui [Dan](person) [e](a_fi) 123456789
- numărul blocului fratelui Mihaelei [e](a_fi) 10
- anul nașterii lui [Ștefan](person) cel Mare [a fost](a_fi) 1433
- numele meu [este](a_fi) Gabriel
- cheile mele de la casă sunt ușoare
- adresa de la serviciu este Bulevardul Unirii nr. 0
- numele asistentului de programare paralelă [e](a_fi) Paul Walker
- suprafața apartamentului de la București [este](a_fi) de 58mp
- prețul canapelei [a fost](a_fi) de 1300 de lei
- codul de activare al sistemului de operare [e](a_fi) APCHF6798HJ67GI90
- sala laboratorului de PP este EG321
- username-ul meu de github [este](a_fi) gabrielboroghina
- seria mea de la buletin [este](a_fi) GG2020
- codul PIN de la cardul meu de sănătate este 0000
- placa mea video este NVidia GeForce GTX950m
- telefonul Karinei este 243243

## intent:get_attr
- [Care](query_word_which) [e](a_fi) mailul lui [Mihai](person)?
- [care](query_word_which) [este](a_fi) numele de utilizator de github [al laborantului de EIM](owner)
- poți să-mi spui [care](query_word_which) era prețul [abonamentului la sală](owner)
- zi-mi [care](query_word_which) a fost câștigătorul concursului Eestec Olympics de anul trecut
- [care](query_word_which) [era](a_fi) denumirea bazei de date de la proiect?
- [care](query_word_which) [sunt](a_fi) tipurile de rețele neurale
- [care](query_word_which) [este](a_fi) valoarea de adevăr a propoziției
- [care](query_word_which) [e](a_fi) adresa colegului meu?
- [care](query_word_which) [e](a_fi) frecvența procesorului meu
- [care](query_word_which) e numărul lui Radu
- [care](query_word_which) [e](a_fi) limita de viteză în localitate
- [care](query_word_which) e punctul de topire al aluminiului
- [care](query_word_which) [e](a_fi) data de naștere a lui Mihai Popa
- [care](query_word_which) [este](a_fi) mărimea mea la adidași
- [care](query_word_which) este temperatura medie în Monaco în iunie
- [care](query_word_which) [este](a_fi) diferența de vârstă între mine și Vlad
- zi-mi și mie [care](query_word_which) era adresa de căsuță poștală a Karinei Preda
- [care](query_word_which) [sunt](a_fi) datele cardului meu revolut
- [care](query_word_which) este telefonul de la frizerie
- care e dobânda de la creditul pentru casă?
- care sunt ministerele cu probleme
- care este tipografia centrală

## intent:get_specifier
- [ce floare](query_word_spec) s-a uscat
- [ce hackathon](query_word_spec) va avea loc săptămâna viitoare
- [ce windows](query_word_spec) am acum pe calculator
- [ce examene](query_word_spec) vor fi date în iunie?
- [ce temperatură](query_word_spec) a fost în iulie anul trecut
- [ce culoare](query_word_spec) au ochii Andreei
- [ce mail](query_word_spec) am folosit la serviciu
- la [ce apartament](query_word_spec) locuiește verișorul meu
- la [ce sală](query_word_spec) se află microscopul electronic
- la [ce număr](query_word_spec) de telefon se dau informații despre situația actuală
- la [care salon](query_word_spec) este internat bunicul lui
- la [care cod](query_word_spec) poștal a fost trimis pachetul
- la [care hotel](query_word_spec) s-au cazat Mihai și Alex ieri
- [ce fel de imprimantă](query_word_spec)  am acasă
- [ce fel de baterie](query_word_spec) folosește ceasul de mână
- [ce fel de procesor](query_word_spec) are telefonul meu
- în [care](query_word_spec) dulap am pus dosarul
- în [care cameră](query_word_spec) am lăsat încărcătorul de telefon
- în [care săptămână](query_word_spec) e examenul de învățare automată
- de la [care prieten](query_word_spec) e cadoul acesta
- de la [care magazin](query_word_spec) mi-am luat cablul de date?
- pentru [ce test](query_word_spec) am învățat acum 2 zile
- pe [care masă](query_word_spec) am pus ieri periuța de dinți?
- pe [care poziție](query_word_spec) este mașina în parcare
- de pe [care cont](query_word_spec) am plătit factura de curent acum 3 zile
- pe [ce viteză](query_word_spec) am setat aerul condiționat
- pe [ce loc](query_word_spec) am ieșit la olimpiada de info din clasa a 12-a
- care aparat de făcut sandwichuri e la reducere
- ce fel de uscător de păr folosește Alice
- care clasificare e corectă
- [care emisferă](query_word_spec) este
- [care elicopter](query_word_spec)
- care autoturism este cel mai prietenos cu mediul
- la ce sprânceană e problema
- la ce fel de neurooftalmologie trebuie să meargă?
- pentru care deversare au fost amedați
- ce fel de pocănit se auzea ieri

## intent:store_timestamp
- concursul va fi pe 12 [ianuarie](time)
- îmi expiră permisul de conducere pe 25 [februarie](time) 2023
- plecarea în Franța este pe 5 [martie](time)
- abonamentul STB îmi expiră pe 23 [aprilie](time)
- Viorel e născut pe 16 [mai](time) [1998](time)
- Vacanța de vară începe pe 30 [iunie](time)
- Pe 3 [iulie](time) se termină sesiunea de licență
- ziua Daianei este în [august](time)
- în [septembrie](time) începe școala
- din [octombrie](time) apare un nou film la cinema
- până în [noiembrie](time) trebuie să termin task-ul
- noile autobuze au apărut în [decembrie](time)
- [luni](time) am fost la alergat
- am mers la bazinul de înot [marți](time)
- garanția de la frigider se termină [marțea](time) viitoare
- coletul cu jacheta va ajunge [miercuri](time)
- testul de curs la rețele neurale a fost [joi](time)
- [vineri](time) încep promoțiile de black friday
- până [sâmbătă](time) e interzis accesul în mall
- Jack a fost la biserică [duminică](time)
- [azi](time) am fost în parcul Titan
- [Mâine](time) vine Mihai pe la mine
- [poimâine](time) merg la mall
- olimpiada internațională de geografie va începe [răspoimâine](time)
- de [ieri](time) s-a făcut cald afară
- am terminat proiecul la programare web [alaltăieri](time)
- procesorul Intel i7 rulează o instrucțiune în 0.3 [nanosecunde](time)
- execuția interogării în baza de date a durat 500 de [milisecunde](time)
- sesiunea din browser a expirat acum 10 [secunde](time)
- prezentarea proiectului durează 45 de [minute](time)
- am de prezentat temele peste o [oră](time)
- am mâncat acum 2 [ore](time)
- peste 3 sferturi de [oră](time) o să ajungă Ina
- întâlnirea cu managerul este peste o jumătate de [oră](time)
- peste 2 [zile](time) începe examenul de bacalaureat
- Maria pleacă în concediu peste 5 [săptămâni](time)
- [săptămâna](time) viitoare încep cursurile de înot
- conferința de bioinformatică a fost acum o [lună](time)
- peste 2 [ani](time) termină Nicoleta masterul
- buletinul îmi expiră peste 3 [ani](time)
- mi-am făcut pașaportul acum un [an](time)
- bătălia de la Mărășești a avut loc în [anul](time) 1917
- acum 5 [decenii](time) nu existau calculatoare
- în [secolul](time) 19 s-a dezvoltat Imperiul lui Napoleon
- [luna](time) viitoare vine Florin din Spania
- meciul dintre Franța și Spania va fi în [weekend](time)
- la [anul](time) se deschide mall-ul din Slatina
- mi-am făcut analize [primăvara](time) trecută
- restricțiile de circulație se încheie la [vară](time)
- [toamna](time) viitoare încep masterul
- Darius și-a schimbat domiciliul [iarna](time) trecută
- curierul o să vină [diseară](time)
- [aseară](time) am făcut cartofi prăjiți
- tonerul de la imprimantă s-a terminat [alaltăseară](time)
- bunica lui Alice va face cozonaci [mâine](time) [dimineață](time)
- [ieri](time) [seara](time) a fost foarte frig afară
- de [dimineață](time) trebuie să hrănesc animalele
- am fost la cumpărături după [amiază](time)
- la [răsărit](time) a început să cânte cocoșul din grădină
- evaluarea națională a ținut 2 [ore](time) și 45 de [minute](time)
- Jacob locuiește în Bremen de un an și 4 [luni](time)
- trebuie să iau antibioticul o dată la 6 [ore](time)
- bazinul de apă se umple o dată la 30 de minute
- Marc ia vitaminele de 2 ori pe [zi](time)
- eu merg la sală de 3 ori pe săptămână
- mgazinul se aprovizionează în fiecare [săptămână](time)
- în fiecare an apare un nou telefon Samsung Galaxy
- serviciul funcționează de [luni](time) până [vineri](time)
- de joi va putea ajunge în Germania cu trenul
- până pe 24 iunie trebuie să trimit lucrarea de diplomă
- festivalul de muzică ușoară și dans va fi de pe 1 septembrie pe 10 octombrie
- de pe 23 până pe 27 am fost în concediu
- între 3 și 7 ianuarie am fost la conferință în Toronto
- la polul nord este noapte timp de 6 [luni](time) 
- Andra și-a ales rochia de bal după 2 [săptămâni](time)
- de la [ora](time) 18 se oprește curentul electric

## intent:get_timestamp
- [când](query_word_time) vor avea loc alegerile locale din 2020
- [Când](query_word_time) am avut ultimul examen anul trecut?
- zi-mi [când](query_word_time) [am fost la sală](action)?
- [De când](query_word_time) [începe vacanța](action)
- [Până când](query_word_time) [trebuie trimisă tema](action)
- [până când](query_word_time) a durat al 2-lea război mondial?
- [până când](query_word_time) trebuie rezolvată problema la vlsi
- [cât timp](query_word_time) [a durat prezentarea temei](action)
- peste [cât timp](query_word_time) se termină starea de urgență?
- peste [cât timp](query_word_time) [începe sesiunea de examene](action)
- când trebuie să merg la control oftalmologic
- [când](query_word_time) trebuie să iau pastilele de stomac
- [cât de des](query_word_time) se actualizează sistemul de operare?
- [cât de des](query_word_time) trebuie să ud florile din fața casei
- [în ce perioadă](time) se va ține concursul de fizică de la Bacău
- [în ce perioadă](time) vor avea loc preselecțiile pentru balul bobocilor 
- [în care perioadă](time) a fost cel mai frig afară?
- [în ce interval](time) e deschis magazinul Kaufland de la Giurgiu?
- [în ce interval](time) de timp a avut loc atacul
- [de când până când](time) se vor închide magazinele
- [de când până când](time) pot citi indexul de energie electrică

## intent:get_subject
- [Cine](query_word_subj) [stă în căminul P16](action)?
- Spune-mi te rog [cine](query_word_subj) [a inventat becul](action)
- [cine](query_word_subj) [a câștigat locul 1 la olimpiada națională de matematică din 2016](action)
- [cine](query_word_subj) [m-a tuns ultima dată](action)?
- de la [cine](query_word_subj) a cumpărat mihaela cireșele
- de la cine a apărut problema
- [cine](query_word_subj) a fost primul om pe lună?
- cine a venit ieri la cursul de astronomie
- zi-mi cine a propus problemele de la concursul InfoOlt 2016

  
## lookup:query_word_loc
  data/lookup-tables/query-word-loc.txt
  
## lookup:query_word_time
  data/lookup-tables/query-word-time.txt

## lookup:person
  data/lookup-tables/person.txt