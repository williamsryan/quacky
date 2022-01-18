
**Policies in s3**

bound: `100`, variables: `True`, constraints: `False`, smt-lib: `False`

|Policy|SAT/UNSAT|Solve Time (ms)|lg(tuple)|Count Time (ms)|lg(principal)|lg(action)|lg(resource)|
|-|-|-|-|-|-|-|-|
|[../samples/s3/exp_single/s3_iam_user_cannot_create_folder_through_console/policy.json](../samples/s3/exp_single/s3_iam_user_cannot_create_folder_through_console/policy.json)|SAT|179.047|5325247487170928987701527726892443772726659812450342610061501412087244598516244378006663805782320816661755867211931409410161518574588691039394319938294196800939573839297132691556347531776359775632260452562185665717555585985102726924488559994331566724495873638782234850958957956328536687911854115203354118011302068920117755388592962255554082629731531225896414974115789470933525967619072524799910560206207082543904357350636323016626149978043808432984434709106461235988046682480890959617781482627985457808473440026110876034405521697700077704658494163507737820308112116840541859557747578805617790666237466178716033587930917751530902784567727805676069188490228821100511607655954023885792731048738725432795107790882832164614364621987597275711522012956632130409696187105205223955752044513028515776782880275895082332860600082078947780525293763712197304557800005597308493096060904859616931413862310757029444722136679710722|108.164|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|330047742842250886728846424023851210387472301353610908831264684114116527328444286877720253256633000861300892163524907778071807513737022987490372691491882719997190504855118092435555373043722209711139968736362753|
|[../samples/s3/exp_single/s3_allow_all_except_delete/fixed.json](../samples/s3/exp_single/s3_allow_all_except_delete/fixed.json)|SAT|358.462|27886467214147730287127964985144673684470323269888783626818476348266874141773841471200119702791147504798366730765566008810853473303552879689326499585877472288219169477260727114742787607113992418977873895978949473546731811112939028864051935122851011870638262664148213400179372842429994808723078995913132123102781808588375366792173379228058260187055966869587231497218549743642833338532794761005400704245137513408093558670072|119.438|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|
|[../samples/s3/exp_single/s3_allow_all_except_delete/initial.json](../samples/s3/exp_single/s3_allow_all_except_delete/initial.json)|SAT|89.5938|27886467214147730287127964985144673684470323269888783626818476348266874141773841471200119702791147504798366730765566008810853473303552879689326499585877472288219169477260727114742747442132538892382336617888265272088958113402176705268580577165474704909365867767722681096038454757516515622257648200862042689841891566359739229240788356547681899879017073668308662121728095218085620098282348632775411863834449796983044331209217|16.4057|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|69890328088575294403204221901046129364173230809567400897352826560957033811407435455053811447876400119158123614791580994342657854187736488943821405020254506560232761555763862593181283582209|
|[../samples/s3/exp_single/s3_public_access/policy.json](../samples/s3/exp_single/s3_public_access/policy.json)|SAT|72.8208|1612170334362925171097650527553323542312830420514235828245276303383597980838648047709863135825547567494011317905038248674529596902394010807885156037435803468397612956530336743327677336803540303425671462704840292440189635365708706900959096148130496558297818266773340270868999945185785505830426163448327541567448819320742878664854265958770045472947190511727843595424603571473097898495613641601830524151059768387190741757195191213248630163657423473986077196151645421745513855045095592696648468710635185452360258588092558250329217291026230552142253069788846290807597389105497267821016253954|8.4082|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|1|57811924399839787871347343458766373941742053008830276169978650432684193664095417464554637334216586512583767999858514780940113122394681259689972951155525368315707649|
|[../samples/s3/exp_single/s3_object_query_permissions/policy1.json](../samples/s3/exp_single/s3_object_query_permissions/policy1.json)|SAT|271.015|89342827345723904547329874204063537942890080631998887243005582474892713474140311438603448108992045322430677123481891032858712392013886580727051323006172315475075196300821331876932899751540886387495195133553689654567075166051828759631912510026899624175769327720694617209841331947151342723763367789652563694747735821866658562511879291967987749831937878157827629815318316122825154768110240543346460327111699560644069208390178503589070547887906238120122810222927777971227862606147472118185354427430891630701969804244237469326750450528508174620691717768252716511162267886500488921217469670965371008461266717366620481577877458916057401971264781424806873637413664194217356494437078294658501842881041850256036462979099538399946051136046085528901823409031692498649534988828037140622191717545487962919217909260690465103976904857323139224195849976627456564429124747551493742156642357443119727391598165205752326264722315006613389313|199.876|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|330047742842250886728846424023851210387472301353610908831264684114116527328444286877720253256633000861300892163524907778071807513737022987490372691491882719997190504855118092435555373043722209711139968736362753|
|[../samples/s3/exp_single/s3_object_query_permissions/fix.json](../samples/s3/exp_single/s3_object_query_permissions/fix.json)|SAT|10.0912|4|4.67857|1|2|1|
|[../samples/s3/exp_single/s3_policy_for_lambda_function/policy2.json](../samples/s3/exp_single/s3_policy_for_lambda_function/policy2.json)|SAT|53.8073|900530020341423242086001912022360221419527901217254772285554329157411832043483501032060994266338641485983931934765426680510629504361594592838735547480289969818451495089315610409054096754668197839620|9.93168|1|4|300176673447141080695333970674120073806509300405751590761851443052470610681161167010686998088779547161994643978255142226836876501453864864279578515826763323272817165029771870136351365584889399279874|
|[../samples/s3/exp_single/s3_policy_for_lambda_function/policy1.json](../samples/s3/exp_single/s3_policy_for_lambda_function/policy1.json)|SAT|223.652|387002474707516950879315278737711670871001247011389029645512754155651709866617935940082402584849034854452369963173169587084730310138537263805004467824253837185665825766100009458393782291923753020544905165394798500421344411557145679367594622681649095760096055924516643691863729803034952023967846350765728289822520158755855241887086614140836767351428799311477023481600695554774451868252901369160606500979201|34.9111|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|969923143031782486511774592233910549157377839612595450643384533697636176888360263413005494357815862704304593827514271919024960918850004744970769235693698697712183420190977|
|[../samples/s3/exp_single/s3_restrict_access_to_certain_roles/policy.json](../samples/s3/exp_single/s3_restrict_access_to_certain_roles/policy.json)|SAT|27.0626|7138935606821818953504759036197036463224402757091528608465529945156319780294103416627230643914533761228381883075984898255578489165709537200467583893984632905784107386178746141374143345185930754456354229232421587486300774117760854707831276851060407663969145091872184826433864656727373051655440003451419926105513571660013016085453252160997602438417695589763946933902864079247637587793066100468271393239627450095199832626168578|3.30287|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|17891923990675275367220280806667809117228347087249254629722323599605000655720303476493775730656358430504479645386644734551720410672060541169618279685185153679419586958275548823854408597045506|
|[../samples/s3/exp_single/s3_bucket_folder_restrict_by_user/policy.json](../samples/s3/exp_single/s3_bucket_folder_restrict_by_user/policy.json)|SAT|1762.43|1498923912429916622953935522774402053792062547020461843035549146401322764337980020681903446569871305421131969900582726797828608873422699400567196486667840694444624242791048148324966980787314840383071108861393743155220721761145876781579734028185013921577513796205197595051288056349760839016917010438901497983372823042315532912004957600262552007626148622950484811354990174243290886931119036626859471294877687368863822465725282697165932071685601418407972280131807827532496137949872695938499042584768736850513280098518843931675288049767312001996903288700889664953895820737397551315950576941031163889017614623335750314754470793025249182094380910390730768399367739990123480239258461276909176030273209427850165417166435463675064535246343055210875434039504626667355798984588900910102699104338442634391436794242362520834664695573074547165373830512387913124319284704787674832619150421579569374143507040051013349167858334722045437271867394|240.571|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|330047742842250886728846424023851210387472301353385081001577809942744076768058480729510323362067257595011913060272235146571434789266106435403589150427102376247743181492070775551201149373058252870688697766379520|
|[../samples/s3/exp_single/s3_remove_permissions_individual_files/policy2.json](../samples/s3/exp_single/s3_remove_permissions_individual_files/policy2.json)|SAT|1341.86|8370866962535629295000422630723339735576724282666201900795925960326060538110737490152548201896160655022947564139123444465517122124389325279014564276898612424992405103940074779148069504037614919960809012165586940436308422706296660216944758800060875033092682799420144725098695526818254412168153838034315477349548548936927530294508924707556670966820052857558025998836707098925773663046229774234645722348933743206570298872208823558666580775391569181602430207955573528985159122974872143482037587018931980607391969852609113400520533047544690008263631091424790818520131256215812448564409323669218357998348346398442902879406340|169.849|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|1|969923143031782486511774592233910549157377839612595450643384533697636176888360263413005494357815862704304593827514271919024960918850004744970769235693698697712183420190977|
|[../samples/s3/exp_single/s3_remove_permissions_individual_files/policy1.json](../samples/s3/exp_single/s3_remove_permissions_individual_files/policy1.json)|UNSAT|108.334|-|-|-|-|-|
|[../samples/s3/exp_single/s3_policy_failing_not_sure_why/policy.json](../samples/s3/exp_single/s3_policy_failing_not_sure_why/policy.json)|SAT|206.13|17880063311394750683873544510385248306436776170711616184790604792237740315901362867522001655599457871568673388238249136398763593118456046459134918641265416488879931031111420219477847148531279313009592604921371659738218605547389188390251900339665956730188075191174940456191874342972288096650235159104004356907214484365286863808083075886204999300742555344121695112337661670452512485586503150443748915577160622126585198303093781673056832180535763420013295039230718889349772247169957822238792505914610207052308562328097180004386374580723234473603304327261681020101140112816150732992788433945835520946121741539997639235701174856348933488617204619459472321348973626540419016773154505451016712276165268620194698322002116095|5401.79|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011354150751007042849718323726680118777457694019123468335457382915296921505289832160501650538515007210368173740611171375254651174973705106873122815|
|[../samples/s3/exp_single/s3_bucket_policy_grant_read_specific_file_type/policy.json](../samples/s3/exp_single/s3_bucket_policy_grant_read_specific_file_type/policy.json)|SAT|26.8424|425513720919002232164428176653208521796727344816418207196326848575849519985562766589357295269640312268041484539269500866864829609734388422993873589872397953616625510822459825359207565549607596369790909821977346148991363046426026696258358824286671971067460796675202123833838644678473259510542299332740214315968707634842179498862235794901875127044800582668602506627571311173710201552070675367220715415010409326426915329|4.34861|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|1|63564883101730897036035659676641561749577914096851055453364848800408284488555578223034728078233820378189305861079975324485219838777753910966404332630422237853265652625635868929|
|[../samples/s3/exp_single/s3_policy_provides_programmatic_access/policy3.json](../samples/s3/exp_single/s3_policy_provides_programmatic_access/policy3.json)|SAT|1688.93|1648084270868188105624042492111032321789988204502872539815313650978116229332066433072633491993916431444602917070642190534159108392894623294153648743280738167791672790785658063687271648338790593874990012079422020880830233702778235229551458762543142894004910517868576042901895699273301729061132578646094893343686616137805879599129039714053431547722102871065902294229341844553707968348147701964579392508473514074072282563377522227058465322385012146426759803140759166370136350762050489408070023680085913029050259328428420850077198862429130754008281226092221817408233038895193086740121533116034491984836581413058168659428243433613629078502146588367425491225871447220083116212799889793393511062094046386724857797027001172319745887812153819087665283809341232160588441463407666407975666534268936597415878854689669266307411672091602195824561898095109154260974090066554015039354817947962444961372252005536468245122893088770040237429151846843973369856|95.1755|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|330047742842250886728846424023851210387472301353610908831264684114116527328444286877720253256633000861300892163524907778071807513737022987490372691491882719997190504855118092435555373043722209711139968736362753|
|[../samples/s3/exp_single/s3_policy_provides_programmatic_access/policy2.json](../samples/s3/exp_single/s3_policy_provides_programmatic_access/policy2.json)|SAT|163.941|25147770246401796045288734315659062527313052436872444760365503707551822346985876969492088195707953360665938065653109596773668035780252430635889415638438997921654151963467072366355895030440349592497648789684302849844964603449331669253078036560366147071739711521632780148416333984040944793982169488875249227569001548393407795216183981030453987281752270308544962859309792191826993682099063699660099439744830304144697504633723727962235048131780122431426224561826996481354175386091135191600727051017969864788868464914765179301746447556059961378805683181936277350436129228522813546256157878925844985607543310809476068488880151581223415810692046005601912101528926498384826104207359588802154817165285386300073496007946207819141392584390449714112850306799593268462843672227465202025683790793334634313947669397125393134030734570736026666072436463887856962566686625049187948222237706723707892621338227770605809812929585785126614245997060156293120|74.5243|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|330047742842250886728846424023851210387472301353610908831264684114116527328444286877720253256633000861300892163524907778071807513737022987490372691491882719997190504855118092435555373043722209711139968736362753|
|[../samples/s3/exp_single/s3_policy_provides_programmatic_access/policy1.json](../samples/s3/exp_single/s3_policy_provides_programmatic_access/policy1.json)|SAT|30.2186|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304515|26.3893|1|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|2|
|[../samples/s3/exp_single/s3_policy_public_and_principal_specific_permissions/policy.json](../samples/s3/exp_single/s3_policy_public_and_principal_specific_permissions/policy.json)|SAT|66.7325|1827567515346385652097218313266441334585447105815431323767175665960017863755290474656571044842120642874465762067452133953428093226421641523319701476860066023880731490861759012191780696367571920173964678639906454527044698128087494529003150391123222627895293031537558309291181031355666606368386978796230908655400757937542938825049233885416418189986986634065150681240699397670861244829146980735928571537396520036837025018536002306|44.5779|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|399003238027526512838915763748543401809079537324548349441603585741471667589232924010119401572526178741032015368498752994665335959886699905716442395518034694662365338464715370235851708859421316392425238882978049004151033770241918304513|273009094095997243762516491800961442828801682849872659755284478753738413325810294746303950968267187965461420370279613259151007242920845659936802363360369166250909224827202588254614388994|
|[../samples/s3/exp_single/s3_sos_bucket_policy_problem/policy.json](../samples/s3/exp_single/s3_sos_bucket_policy_problem/policy.json)|SAT|68512.8|3672372161614756308327871205551675103670536653055759138350652822274436647943694509350044096301960984365232202457557328282579632284975308461391612013946986968253821058271974656125475710515804255015855870291490369753451971458342959356086682115619631106607724745805353851123825360449522060011060685744984671523166313783295141897039491557104858302457813277502013390737931440108808287692736341102877736047030857151950778860873334357559796249321685539838265730603939943783718324193535139817610047503813754919234610972008974464276034531110601192018051356840685435438336926110174388231137328280559035444895143082114995494861576594636456626612587914267328631773407720651606705357380146945988884840335692069474587611281283880437633094159516562187597136089087450582735298416839018825400554258461896306913968241421099969771582551325777842194276232761981206615347876706577945605|124831|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|17891923990675275367220280806667809117228347087249254629722323599605000655720303476493775730656358430504479645386644734551720410672060541169618279685185153679419586958275548823854408597045505|
|[../samples/s3/exp_single/s3_policy_or_condition/policy.json](../samples/s3/exp_single/s3_policy_or_condition/policy.json)|SAT|624.778|729205356337129137578456468102538302795171041252841101750726335165151475008594736295142707206520768768354165097281506510025911087085251039677111823092287218956987771432377094384308748931031149008377181159324212692044649265728256895060446701165021188653337965374880422273557273755780930972813832860939645977142011590719649396309617193504101666948669210591107807873573323807053122042040633005601019696630209051016173024803955689201954767667512733013909142662728032427547925681836482074197016956672554950423931721994099025047539156349927374137042348172158861278434992952793838584424189876225150622962236592196194315813317422768491867711665517178799424847475574787|127.345|6694163509087226251625262974214282337525718158874009761025262744359190325024760040429359385973011366392902184752623174722147189111586499845384388821163499967844550354335638144966855063503625060120058996591321451401226790186643035649168441601|1|76845228402468116658005496492574738894466380903872407235033969421432476334377258754735871510727564073470628858433316410070240384372189405255572100051651410757841194247621598754905949589731686215647489|