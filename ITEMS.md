# Items
Successfully preserving all 94 official DLC items was relatively straightforward. The extracted files of *The Legend 
of Zelda: Skyward Sword Save Data Update Channel* contain several ACCF assets. In fact, several pieces of information 
suggest that the application was built upon a tool previously developed specifically for ACCF. Among the channel's 
files is an archive containing 256 item data files in the proprietary ``BITM`` format. These files include the 94 DLC
items along with duplicates of the cardboard box item used as fillers for unused slots. Curiously, three items that 
Nintendo never officially released via WiiConnect24 were discovered thanks to these extracted files: the blue Pikmin, 
red Pikmin, and red headgear. All of these made their official debut in *Animal Crossing: New Leaf*.

The table below lists all 256 item slots, including each slot's internal name from the Zelda application, the item's 
unique inventory ID and its American English name. All dumped item BITM files can be found [in the items folder](items).

| Slot ID | Slot name           | Tokenized ID | Item name        |
|:-------:|---------------------|:------------:|------------------|
|    0    | ``ADD_WALL_00``     |  ``A130h``   | Sporty wall      |
|    1    | ``ADD_WALL_01``     |  ``A134h``   |                  |
|    2    | ``ADD_WALL_02``     |  ``A138h``   | Golden wallpaper |
|    3    | ``ADD_WALL_03``     |  ``A13Ch``   | Creepy wallpaper |
|    4    | ``ADD_WALL_04``     |  ``A140h``   |                  |
|    5    | ``ADD_WALL_05``     |  ``A144h``   |                  |
|    6    | ``ADD_WALL_06``     |  ``A148h``   |                  |
|    7    | ``ADD_WALL_07``     |  ``A14Ch``   |                  |
|    8    | ``ADD_WALL_08``     |  ``A150h``   |                  |
|    9    | ``ADD_WALL_09``     |  ``A154h``   |                  |
|   10    | ``ADD_WALL_10``     |  ``A158h``   |                  |
|   11    | ``ADD_WALL_11``     |  ``A15Ch``   |                  |
|   12    | ``ADD_WALL_12``     |  ``A160h``   |                  |
|   13    | ``ADD_WALL_13``     |  ``A164h``   |                  |
|   14    | ``ADD_WALL_14``     |  ``A168h``   |                  |
|   15    | ``ADD_WALL_15``     |  ``A16Ch``   |                  |
|   16    | ``ADD_UMBRELLA_00`` |  ``ABE0h``   | Ghost umbrella   |
|   17    | ``ADD_UMBRELLA_01`` |  ``ABE4h``   | Maple umbrella   |
|   18    | ``ADD_UMBRELLA_02`` |  ``ABE8h``   |                  |
|   19    | ``ADD_UMBRELLA_03`` |  ``ABECh``   |                  |
|   20    | ``ADD_UMBRELLA_04`` |  ``ABF0h``   |                  |
|   21    | ``ADD_UMBRELLA_05`` |  ``ABF4h``   |                  |
|   22    | ``ADD_UMBRELLA_06`` |  ``ABF8h``   |                  |
|   23    | ``ADD_UMBRELLA_07`` |  ``ABFCh``   |                  |
|   24    | ``ADD_UMBRELLA_08`` |  ``AC00h``   |                  |
|   25    | ``ADD_UMBRELLA_09`` |  ``AC04h``   |                  |
|   26    | ``ADD_UMBRELLA_10`` |  ``AC08h``   |                  |
|   27    | ``ADD_UMBRELLA_11`` |  ``AC0Ch``   |                  |
|   28    | ``ADD_UMBRELLA_12`` |  ``AC10h``   |                  |
|   29    | ``ADD_UMBRELLA_13`` |  ``AC14h``   |                  |
|   30    | ``ADD_UMBRELLA_14`` |  ``AC18h``   |                  |
|   31    | ``ADD_UMBRELLA_15`` |  ``AC1Ch``   |                  |
|   32    | ``ADD_CAP_00``      |  ``AD70h``   | Shamrock hat     |
|   33    | ``ADD_CAP_01``      |  ``AD74h``   | Student cap      |
|   34    | ``ADD_CAP_02``      |  ``AD78h``   | Flamenco hat     |
|   35    | ``ADD_CAP_03``      |  ``AD7Ch``   | Red team hat     |
|   36    | ``ADD_CAP_04``      |  ``AD80h``   | White team hat   |
|   37    | ``ADD_CAP_05``      |  ``AD84h``   |                  |
|   38    | ``ADD_CAP_06``      |  ``AD88h``   | Hot dog hat      |
|   39    | ``ADD_CAP_07``      |  ``AD8Ch``   | Celebration hat  |
|   40    | ``ADD_CAP_08``      |  ``AD90h``   | Emperor's cap    |
|   41    | ``ADD_CAP_09``      |  ``AD94h``   | Banana split hat |
|   42    | ``ADD_CAP_10``      |  ``AD98h``   | School cap       |
|   43    | ``ADD_CAP_11``      |  ``AD9Ch``   | White school cap |
|   44    | ``ADD_CAP_12``      |  ``ADA0h``   | White police cap |
|   45    | ``ADD_CAP_13``      |  ``ADA4h``   |                  |
|   46    | ``ADD_CAP_14``      |  ``ADA8h``   |                  |
|   47    | ``ADD_CAP_15``      |  ``ADACh``   |                  |
|   48    | ``ADD_EXCAP_00``    |  ``AEB0h``   | Red Pikmin       |
|   49    | ``ADD_EXCAP_01``    |  ``AEB4h``   | Blue Pikmin      |
|   50    | ``ADD_EXCAP_02``    |  ``AEB8h``   | Yellow Pikmin    |
|   51    | ``ADD_EXCAP_03``    |  ``AEBCh``   | Girl's day updo  |
|   52    | ``ADD_EXCAP_04``    |  ``AEC0h``   | Green headgear   |
|   53    | ``ADD_EXCAP_05``    |  ``AEC4h``   | Red headgear     |
|   54    | ``ADD_EXCAP_06``    |  ``AEC8h``   | Snowman head     |
|   55    | ``ADD_EXCAP_07``    |  ``AECCh``   | Tsunokakushi     |
|   56    | ``ADD_EXCAP_08``    |  ``AED0h``   | Kintaro wig      |
|   57    | ``ADD_EXCAP_09``    |  ``AED4h``   | Guard's helmet   |
|   58    | ``ADD_EXCAP_10``    |  ``AED8h``   | Tam o'shanter    |
|   59    | ``ADD_EXCAP_11``    |  ``AEDCh``   | Red horned hat   |
|   60    | ``ADD_EXCAP_12``    |  ``AEE0h``   |                  |
|   61    | ``ADD_EXCAP_13``    |  ``AEE4h``   |                  |
|   62    | ``ADD_EXCAP_14``    |  ``AEE8h``   |                  |
|   63    | ``ADD_EXCAP_15``    |  ``AEECh``   |                  |
|   64    | ``ADD_ACC_00``      |  ``B0D0h``   | Ladder shades    |
|   65    | ``ADD_ACC_01``      |  ``B0D4h``   |                  |
|   66    | ``ADD_ACC_02``      |  ``B0D8h``   |                  |
|   67    | ``ADD_ACC_03``      |  ``B0DCh``   |                  |
|   68    | ``ADD_ACC_04``      |  ``B0E0h``   |                  |
|   69    | ``ADD_ACC_05``      |  ``B0E4h``   |                  |
|   70    | ``ADD_ACC_06``      |  ``B0E8h``   |                  |
|   71    | ``ADD_ACC_07``      |  ``B0ECh``   |                  |
|   72    | ``ADD_ACC_08``      |  ``B0F0h``   |                  |
|   73    | ``ADD_ACC_09``      |  ``B0F4h``   |                  |
|   74    | ``ADD_ACC_10``      |  ``B0F8h``   |                  |
|   75    | ``ADD_ACC_11``      |  ``B0FCh``   |                  |
|   76    | ``ADD_ACC_12``      |  ``B100h``   |                  |
|   77    | ``ADD_ACC_13``      |  ``B104h``   |                  |
|   78    | ``ADD_ACC_14``      |  ``B108h``   |                  |
|   79    | ``ADD_ACC_15``      |  ``B10Ch``   |                  |
|   80    | ``ADD_FTR_000``     |  ``C840h``   | Top              |
|   81    | ``ADD_FTR_001``     |  ``C844h``   | Tokonoma         |
|   82    | ``ADD_FTR_002``     |  ``C848h``   | Nintendo DSi W   |
|   83    | ``ADD_FTR_003``     |  ``C84Ch``   | Carp banner      |
|   84    | ``ADD_FTR_004``     |  ``C850h``   | Eggplant cow     |
|   85    | ``ADD_FTR_005``     |  ``C854h``   | Nintendo DSi B   |
|   86    | ``ADD_FTR_006``     |  ``C858h``   | Bus model        |
|   87    | ``ADD_FTR_007``     |  ``C85Ch``   | Morning glory    |
|   88    | ``ADD_FTR_008``     |  ``C860h``   | Eiffel Tower     |
|   89    | ``ADD_FTR_009``     |  ``C864h``   | Dolphin model    |
|   90    | ``ADD_FTR_010``     |  ``C868h``   | Gamecube dresser |
|   91    | ``ADD_FTR_011``     |  ``C86Ch``   | Pile of leaves   |
|   92    | ``ADD_FTR_012``     |  ``C870h``   | Sand castle      |
|   93    | ``ADD_FTR_013``     |  ``C874h``   | Shopping cart    |
|   94    | ``ADD_FTR_014``     |  ``C878h``   |                  |
|   95    | ``ADD_FTR_015``     |  ``C87Ch``   | Chihuahua model  |
|   96    | ``ADD_FTR_016``     |  ``C880h``   | Dalmatian model  |
|   97    | ``ADD_FTR_017``     |  ``C884h``   | Dachshund model  |
|   98    | ``ADD_FTR_018``     |  ``C888h``   | Labrador model   |
|   99    | ``ADD_FTR_019``     |  ``C88Ch``   | Election poster  |
|   100   | ``ADD_FTR_020``     |  ``C890h``   | Anniversary cake |
|   101   | ``ADD_FTR_021``     |  ``C894h``   | Festive wreath   |
|   102   | ``ADD_FTR_022``     |  ``C898h``   |                  |
|   103   | ``ADD_FTR_023``     |  ``C89Ch``   | Wii locker       |
|   104   | ``ADD_FTR_024``     |  ``C8A0h``   | Hagoita          |
|   105   | ``ADD_FTR_025``     |  ``C8A4h``   | Blossom lantern  |
|   106   | ``ADD_FTR_026``     |  ``C8A8h``   | Cucumber horse   |
|   107   | ``ADD_FTR_027``     |  ``C8ACh``   | Nintendo DS Lite |
|   108   | ``ADD_FTR_028``     |  ``C8B0h``   |                  |
|   109   | ``ADD_FTR_029``     |  ``C8B4h``   |                  |
|   110   | ``ADD_FTR_030``     |  ``C8B8h``   |                  |
|   111   | ``ADD_FTR_031``     |  ``C8BCh``   |                  |
|   112   | ``ADD_FTR_032``     |  ``C8C0h``   | Fedora chair     |
|   113   | ``ADD_FTR_033``     |  ``C8C4h``   |                  |
|   114   | ``ADD_FTR_034``     |  ``C8C8h``   | Kapp'n model     |
|   115   | ``ADD_FTR_035``     |  ``C8CCh``   |                  |
|   116   | ``ADD_FTR_036``     |  ``C8D0h``   |                  |
|   117   | ``ADD_FTR_037``     |  ``C8D4h``   |                  |
|   118   | ``ADD_FTR_038``     |  ``C8D8h``   |                  |
|   119   | ``ADD_FTR_039``     |  ``C8DCh``   |                  |
|   120   | ``ADD_FTR_040``     |  ``C8E0h``   |                  |
|   121   | ``ADD_FTR_041``     |  ``C8E4h``   | Tteok plate      |
|   122   | ``ADD_FTR_042``     |  ``C8E8h``   | Kimbap plate     |
|   123   | ``ADD_FTR_043``     |  ``C8ECh``   | Samgyetang bowl  |
|   124   | ``ADD_FTR_044``     |  ``C8F0h``   | Shaved ice lamp  |
|   125   | ``ADD_FTR_045``     |  ``C8F4h``   |                  |
|   126   | ``ADD_FTR_046``     |  ``C8F8h``   | Flower bouquet   |
|   127   | ``ADD_FTR_047``     |  ``C8FCh``   | Cupid bench      |
|   128   | ``ADD_FTR_048``     |  ``C900h``   |                  |
|   129   | ``ADD_FTR_049``     |  ``C904h``   |                  |
|   130   | ``ADD_FTR_050``     |  ``C908h``   |                  |
|   131   | ``ADD_FTR_051``     |  ``C90Ch``   | Snowman vanity   |
|   132   | ``ADD_FTR_052``     |  ``C910h``   | Mushroom rack    |
|   133   | ``ADD_FTR_053``     |  ``C914h``   | Pavé clock       |
|   134   | ``ADD_FTR_054``     |  ``C918h``   | Egg tv           |
|   135   | ``ADD_FTR_055``     |  ``C91Ch``   | Jingle tv        |
|   136   | ``ADD_FTR_056``     |  ``C920h``   | Gracie dresser   |
|   137   | ``ADD_FTR_057``     |  ``C924h``   | Sweets player    |
|   138   | ``ADD_FTR_058``     |  ``C928h``   |                  |
|   139   | ``ADD_FTR_059``     |  ``C92Ch``   | Golden bed       |
|   140   | ``ADD_FTR_060``     |  ``C930h``   | Golden dresser   |
|   141   | ``ADD_FTR_061``     |  ``C934h``   | Golden closet    |
|   142   | ``ADD_FTR_062``     |  ``C938h``   | Golden chair     |
|   143   | ``ADD_FTR_068``     |  ``C93Ch``   | Golden bench     |
|   144   | ``ADD_FTR_063``     |  ``C940h``   | Golden table     |
|   145   | ``ADD_FTR_064``     |  ``C944h``   | Golden clock     |
|   146   | ``ADD_FTR_065``     |  ``C948h``   | Golden man       |
|   147   | ``ADD_FTR_066``     |  ``C94Ch``   | Golden woman     |
|   148   | ``ADD_FTR_067``     |  ``C950h``   | Golden screen    |
|   149   | ``ADD_FTR_069``     |  ``C954h``   | Creepy skeleton  |
|   150   | ``ADD_FTR_070``     |  ``C958h``   | Creepy cauldron  |
|   151   | ``ADD_FTR_071``     |  ``C95Ch``   | Creepy bat stone |
|   152   | ``ADD_FTR_072``     |  ``C960h``   | Creepy stone     |
|   153   | ``ADD_FTR_073``     |  ``C964h``   | Creepy coffin    |
|   154   | ``ADD_FTR_074``     |  ``C968h``   | Creepy crystal   |
|   155   | ``ADD_FTR_075``     |  ``C96Ch``   | Creepy clock     |
|   156   | ``ADD_FTR_076``     |  ``C970h``   | Creepy statue    |
|   157   | ``ADD_FTR_077``     |  ``C974h``   |                  |
|   158   | ``ADD_FTR_078``     |  ``C978h``   |                  |
|   159   | ``ADD_FTR_079``     |  ``C97Ch``   |                  |
|   160   | ``ADD_FTR_080``     |  ``C980h``   |                  |
|   161   | ``ADD_FTR_081``     |  ``C984h``   |                  |
|   162   | ``ADD_FTR_082``     |  ``C988h``   |                  |
|   163   | ``ADD_FTR_083``     |  ``C98Ch``   |                  |
|   164   | ``ADD_FTR_084``     |  ``C990h``   |                  |
|   165   | ``ADD_FTR_085``     |  ``C994h``   |                  |
|   166   | ``ADD_FTR_086``     |  ``C998h``   |                  |
|   167   | ``ADD_FTR_087``     |  ``C99Ch``   |                  |
|   168   | ``ADD_FTR_088``     |  ``C9A0h``   |                  |
|   169   | ``ADD_FTR_089``     |  ``C9A4h``   |                  |
|   170   | ``ADD_FTR_090``     |  ``C9A8h``   |                  |
|   171   | ``ADD_FTR_091``     |  ``C9ACh``   |                  |
|   172   | ``ADD_FTR_092``     |  ``C9B0h``   |                  |
|   173   | ``ADD_FTR_093``     |  ``C9B4h``   |                  |
|   174   | ``ADD_FTR_094``     |  ``C9B8h``   |                  |
|   175   | ``ADD_FTR_095``     |  ``C9BCh``   |                  |
|   176   | ``ADD_FTR_096``     |  ``C9C0h``   |                  |
|   177   | ``ADD_FTR_097``     |  ``C9C4h``   |                  |
|   178   | ``ADD_FTR_098``     |  ``C9C8h``   |                  |
|   179   | ``ADD_FTR_099``     |  ``C9CCh``   |                  |
|   180   | ``ADD_FTR_100``     |  ``C9D0h``   |                  |
|   181   | ``ADD_FTR_101``     |  ``C9D4h``   |                  |
|   182   | ``ADD_FTR_102``     |  ``C9D8h``   |                  |
|   183   | ``ADD_FTR_103``     |  ``C9DCh``   |                  |
|   184   | ``ADD_FTR_104``     |  ``C9E0h``   |                  |
|   185   | ``ADD_FTR_105``     |  ``C9E4h``   |                  |
|   186   | ``ADD_FTR_106``     |  ``C9E8h``   |                  |
|   187   | ``ADD_FTR_107``     |  ``C9ECh``   |                  |
|   188   | ``ADD_FTR_108``     |  ``C9F0h``   |                  |
|   189   | ``ADD_FTR_109``     |  ``C9F4h``   |                  |
|   190   | ``ADD_FTR_110``     |  ``C9F8h``   |                  |
|   191   | ``ADD_FTR_111``     |  ``C9FCh``   |                  |
|   192   | ``ADD_FTR_115``     |  ``CA0Ch``   |                  |
|   193   | ``ADD_FTR_116``     |  ``CA10h``   |                  |
|   194   | ``ADD_FTR_117``     |  ``CA14h``   |                  |
|   195   | ``ADD_FTR_118``     |  ``CA18h``   |                  |
|   196   | ``ADD_FTR_119``     |  ``CA1Ch``   |                  |
|   197   | ``ADD_FTR_120``     |  ``CA20h``   |                  |
|   198   | ``ADD_FTR_121``     |  ``CA24h``   |                  |
|   199   | ``ADD_FTR_122``     |  ``CA28h``   |                  |
|   200   | ``ADD_FTR_123``     |  ``CA2Ch``   |                  |
|   201   | ``ADD_FTR_124``     |  ``CA30h``   |                  |
|   202   | ``ADD_FTR_125``     |  ``CA34h``   |                  |
|   203   | ``ADD_FTR_126``     |  ``CA38h``   |                  |
|   204   | ``ADD_FTR_127``     |  ``CA3Ch``   |                  |
|   205   | ``ADD_FTR_128``     |  ``CA40h``   |                  |
|   206   | ``ADD_FTR_129``     |  ``CA44h``   |                  |
|   207   | ``ADD_FTR_130``     |  ``CA48h``   |                  |
|   208   | ``ADD_FTR_112``     |  ``CA00h``   |                  |
|   209   | ``ADD_FTR_113``     |  ``CA04h``   |                  |
|   210   | ``ADD_FTR_114``     |  ``CA08h``   |                  |
|   211   | ``ADD_FTR_131``     |  ``CA4Ch``   |                  |
|   212   | ``ADD_FTR_132``     |  ``CA50h``   |                  |
|   213   | ``ADD_FTR_133``     |  ``CA54h``   |                  |
|   214   | ``ADD_FTR_134``     |  ``CA58h``   |                  |
|   215   | ``ADD_FTR_135``     |  ``CA5Ch``   |                  |
|   216   | ``ADD_FTR_136``     |  ``CA60h``   |                  |
|   217   | ``ADD_FTR_137``     |  ``CA64h``   |                  |
|   218   | ``ADD_FTR_138``     |  ``CA68h``   |                  |
|   219   | ``ADD_FTR_139``     |  ``CA6Ch``   |                  |
|   220   | ``ADD_FTR_140``     |  ``CA70h``   |                  |
|   221   | ``ADD_FTR_141``     |  ``CA74h``   |                  |
|   222   | ``ADD_FTR_142``     |  ``CA78h``   |                  |
|   223   | ``ADD_FTR_143``     |  ``CA7Ch``   |                  |
|   224   | ``ADD_FTR_144``     |  ``CA80h``   |                  |
|   225   | ``ADD_FTR_145``     |  ``CA84h``   |                  |
|   226   | ``ADD_FTR_146``     |  ``CA88h``   |                  |
|   227   | ``ADD_FTR_147``     |  ``CA8Ch``   |                  |
|   228   | ``ADD_FTR_148``     |  ``CA90h``   |                  |
|   229   | ``ADD_FTR_149``     |  ``CA94h``   |                  |
|   230   | ``ADD_FTR_150``     |  ``CA98h``   |                  |
|   231   | ``ADD_FTR_151``     |  ``CA9Ch``   |                  |
|   232   | ``ADD_FTR_152``     |  ``CAA0h``   |                  |
|   233   | ``ADD_FTR_153``     |  ``CAA4h``   |                  |
|   234   | ``ADD_FTR_154``     |  ``CAA8h``   |                  |
|   235   | ``ADD_FTR_155``     |  ``CAACh``   |                  |
|   236   | ``ADD_FTR_156``     |  ``CAB0h``   |                  |
|   237   | ``ADD_FTR_157``     |  ``CAB4h``   |                  |
|   238   | ``ADD_FTR_158``     |  ``CAB8h``   |                  |
|   239   | ``ADD_FTR_159``     |  ``CABCh``   |                  |
|   240   | ``ADD_CARPET_00``   |  ``A450h``   | Hopscotch floor  |
|   241   | ``ADD_CARPET_01``   |  ``A454h``   | Sporty floor     |
|   242   | ``ADD_CARPET_02``   |  ``A458h``   | Wildflower floor |
|   243   | ``ADD_CARPET_03``   |  ``A45Ch``   | Golden carpet    |
|   244   | ``ADD_CARPET_04``   |  ``A460h``   | Creepy carpet    |
|   245   | ``ADD_CARPET_05``   |  ``A464h``   |                  |
|   246   | ``ADD_CARPET_06``   |  ``A468h``   |                  |
|   247   | ``ADD_CARPET_07``   |  ``A46Ch``   |                  |
|   248   | ``ADD_CARPET_08``   |  ``A470h``   |                  |
|   249   | ``ADD_CARPET_09``   |  ``A474h``   |                  |
|   250   | ``ADD_CARPET_10``   |  ``A478h``   |                  |
|   251   | ``ADD_CARPET_11``   |  ``A47Ch``   |                  |
|   252   | ``ADD_CARPET_12``   |  ``A480h``   |                  |
|   253   | ``ADD_CARPET_13``   |  ``A484h``   |                  |
|   254   | ``ADD_CARPET_14``   |  ``A488h``   |                  |
|   255   | ``ADD_CARPET_15``   |  ``A48Ch``   |                  |
