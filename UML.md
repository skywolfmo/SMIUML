---
marp: true
theme: gaia
class: lead
paginate: true
backgroundImage: url('hero-background.jpg')
header: '**Preparation UML**'
footer: Taha Bouhsine

---

# UML SMI5  
<!-- 
- lgoal ta3 SE
- OOP ou les pricipes
- lfer9 bin association, aggregation, w composition
- w les diagram li kaynin 3ndna bi 3oujala
- w semain jaya in chae allah n7awel ndir chi 7issa khra nsse7ou fiha l exam dl3am li fat.
- anb9a nsste9bel les qst ta3koum hna li 3ndou chi sou2al yssewel ila mafhemch chi 7aja, mli nssali chi part ankhlli w9ita sghira bach ila matfehmatch chi 7aja n3awdha
-->

## Join this link

## https://app.sli.do/event/ex3esarj

---

## Software Engineer Goal

---

![bg width:80%](modeling.png)

<!-- 
role ta3 software engineer houwa y7awel ycree wa7ed reality jdida mn reality li intale9 mnha, 
- walakin houwa lewel kaykhessoou yfhem reality li houwa fiha
- bach yfhemha khassou ycree des model, est alors creea wa7ed reality jdida
- 3ad kay7awel ybesset awla ydir labstract ldik reality li creea b des models khriin
- 3aaad kayfhem reality lewla li kan fiha mzyan
 -->

---

What, Why , How?

<!-- ou fi lekher kay7awl yl9a bhadchi l2ajwiba ta3 3 lass2ila 
Achnou?
3lach?
kifach?

mli kayssali had les model kaykoun safi fhem reality dyalou ou wajed bach ybda lcode

-->

---

## Object Oriented Programming

![bg right ](oop_meme.jpg)

---

<!-- 
mn bin l7wayj l2assasya li kat2amn bihoum had lparadigm awla namoudaj ta3 OOP
houwa annaha kat3amel koulchi b7al objets ay achya2
 -->

Everything is an object

---
<!-- W 3ndha des pricipes li katkhdem bihoum bach ttebe9 had lparadigm dyalha -->
### Principles of object-oriented programming

---

Question

---

![bg width:50%](oo_fund.png)

---

### Abstraction (representing)

![bg right ](abstract.jpeg)

<!-- 
Mli kanchoufou l7wayj li 9damna koul 7aja kanbdaw n7awlou nl9aw chi 7aja bach nwessfouha, swa mn na7it chkel. Ta3ha, type ta3ha, awla mnach mssnou3a,

Daba matalan lkrassa 3ndna lkrassa ta3 l7did ta3 lkhcheb ta3 lplasstik, walakin koulhoum krassa, hadi hya l abstraction,7na fi lkher kayhemna gha billa rah hadak koursi kan9drou nguelssou fou9ou
-->

---

Objects in an OOP language provide an abstraction that hides the internal implementation details. Similar to the coffee machine in your kitchen, you just need to know which methods of the object are available to call and which input parameters are needed to trigger a specific operation. But you don’t need to understand how this method is implemented and which kinds of actions it has to perform to create the expected result.

---

![bg width:70%](abstraction.png)

---

### Classification

<!-- 
3ad 3ndna 3awtani lkrassa tballi lvetrinat wkoulhoum kanjem3ouhoum fi fournitures hadi hya lclassification, y9drou ybanou likoum kaytchabhou mais rah chi mrtabt bchi fi had les principes
-->

---

Ask Question?

---

![bg width:70%](classification.png)

---

### Encapsulation

![bg right width:100%](encapsu_meme.jpg)

<!-- 
Of coirse 3yitou makatssem3ou fi hadi w3yitou makatssem3ou fi l9wilbat w fi les capsule mais 3laaach, had l encapsulation kat9der awaln tproteger les donnees ta3na, w kat9der thenni dev mn bach yb9a 3aref gua3 les attribute li kaynin ou la valeur wella l etat li kayn fiha l object, houwa kay3ref gha les method, 3eyet lihoum ou khdmou lih tabaraka llah, makhdmouch lih dikssa3a kay9der yl9a lbug dghya bla mayberzet rassou

 -->

---

Question

---

 showcasing only the required things to the outside world while hiding the details. Continuing our example, Human Being's can talk, walk, hear, eat, but the details are hidden from the outside world. We can take our skin as the Encapsulation factor in our case, hiding the inside mechanism.

---

![bg width:70%](encapsulation.png)

---

### Association (Relating)

<!-- 
Kanguoulou wa7ed associer m3a wa7ed wakha tkoun gha kat3arfou, wakha ykoun gha 9errak matalan awlla mataln 3chirek

Katzid tspecify  had association ll aggregamli katl9a 3ndek chi 3ala9a watida m3a dak chekhss, matalan wella 3chirek 3chirtek, awla chi 7aja khra dakchi binatkoum massou9ich ana.
 -->
---

Question

---

Objects are classified and abstracted into classes. Classes don’t exist in isolation. They relate to other classes in multiple ways. The association relationship is a mechanism for two (more) classes to relate to each other. For example, the class Person associating with the class Clock in order to achieve the objective of, say, “find the time.” There can be many additional associations between Person and Clock such as “changing the batteries of a clock,” “buying a clock,” or “setting the time.”

---

![bg width:70%](association.png)

---

### Inheritance (Generalizing)

<!-- 
Wa7ed mn biin lprincipe lmouhimin fi oop, kat9der tl9a languages li ma3ndhomch lencapsulation matalan, mais ila makantch hadi rah gha kayde7kou 3la lwe9t ila gualou lik rah hadik language oop.

7itach bssbabha kat9der tkhedem lpolymorph, l abstraction ou chi twacha khrin atfehmouhoum mn be3d

Daba matalan koul wa7ed ach kay heriti mn walidih,kayn li wreth lflouss, zrou9ya dl3inin, sekkar, sguou3ya mouhim koul wa7ed ach khda, 

 -->

---

Question

---

Considering HumanBeing a class, which has properties like hands, legs, eyes etc, and functions like walk, talk, eat, see etc. Male and Female are also classes, but most of the properties and functions are included in HumanBeing, hence they can inherit everything from class HumanBeing using the concept of Inheritance.

---

### Polymorphism (Executing)

![bg right width:90%](poly_meme.jpg)

<!-- 
Koul wa7ed ach mrebbi
Chi mchach chi klab chi 9rouda
Linfrid koul wa7ed fikoum mcha traina b l7ayaqan dyalou bach mli yguoul lih dwi, yguoul chi 7aja, 
Mli nji ana , makayhemnich achmen type l7ayawan dyalk, li kayhemni houwa mli nguoul lih dwi yguoul li chi 7aja,

Koulhoum 7ayawanat
Walaki Koul wa7ed kifach kayguoul liha

Kan9drou nwsslou liha b l inheritance w b abstraction


 -->

---

Question

---

Polymorphism is a concept, which allows us to redefine the way something works, by either changing how it is done or by changing the parts using which it is done. Both the ways have different terms for them.

If we walk using our hands, and not legs, here we will change the parts used to perform something. Hence this is called **Overloading**.

And if there is a defined way of walking, but I wish to walk differently, but using my legs, like everyone else. Then I can walk like I want, this will be called as **Overriding**.

---

![width:500](poly_mem.jpeg)

---

![bg width:60%](polymorphisme.png)

---

### Class

![bg right width:100%](classes_dino_meme.png)
<!-- 
bnsba ll class n9drou n3tabrouha hya lcode adn ta3 les objet li kaytcreeaw mnha, bach we9t l execution mli ybghi lcompilateur ykhdem yl9a lmoule awla l9alb bach y9der y9ad douk les objet li bgha
-->

---

<!-- 
mital daba lclass ta3 human being li kat3eref lina ach kaykhess ykoun 3nd had lhuman being bach ykoun human being, rjlin lidin 3inin rass ilakh
-->
Here we can take Human Being as a class. A class is a blueprint for any functional entity which defines its properties and its functions. Like Human Being, having body parts, and performing various actions.

---
<!-- 
ou kimma guelna OOP kat3taber koulchi object, 
 -->

### Objects

![bg right width:100%](object_meme.jpg)

---

<!-- 
matalan ana smeyti taha, ana objet ta3 class human awla human. dik lhuman being , rajl, mra kan3tabrouh gha wa7ed lkind awla naw3, nta w ana w nass lkhrin gha wa7ed lform mtjessda ta3 dak naw3. 3ndna l existance ta3na physique, amma lclass hya gha wa7ed definition logic, ou 7na houma les object
 -->

My name is Taha, and I am an instance/object of class Male. When we say, Human Being, Male or Female, we just mean a kind, you, your friend, me we are the forms of these classes. We have a physical existence while a class is just a logical definition. We are the objects.

---

Ask Questions?

---

### Positives

---

- Design first then code
- resue of code
- easy to maintain and modify

---

## Association
<!-- 
Kanguoulou wa7ed associer m3a wa7ed wakha tkoun gha kat3arfou, wakha ykoun gha 9errak matalan awlla mataln 3chirek

Katzid tspecify  had association ll aggregamli katl9a 3ndek chi 3ala9a watida m3a dak chekhss, matalan wella 3chirek 3chirtek.
-->
---

<!-- ri7t che7ma fi cha9our -->
![width:400](association_diag.png)

---

    class Department
    {
    int DeptID;
    String DeptName;
    int[] AllDoctors;
    int HospitalID;
    // Start Methods
    // Getters and Setters
        Doctor getDoctor(int doctorId){
        }
        Hospital getHospital(Hospital hospitals){
        }
    }

---

![width:600](Associatn.png)

---

Ask Questions?

---

## Agregation: Has-A

<!-- 
Bach tfehmou l aggregarion mzyan, nakhdou example ta3 tonobila, tonobila katkoun 3ndha rwayd donc kan9drou nguoulou tonobile made of 4 rwayd
Walakin kat7ewel l composition ila jab llah l9ina billa tonobil mzdyiin m3aha rwayd ou makanl9awhoumcb kaytba3ou bou7dhum, amma bnnssba lina kan9drou nchriw rwayed w nchriw jaj ou dakchi
-->

---
An aggregation relationship is a specialized form of association. In aggregation, classes are related more closely to each other than in an association relationship. Aggregation can be described as a whole–part relationship wherein an entity is “made up of” or “composed of” other entities, or classes.

---

![width:600](aggregation_diag.png)

---

    class Department
    {
    int DeptID;
    String DeptName;
    int[] AllDoctors;
    int HospitalID;
    // Methods
    // Getters and Setters
    }
    
    class Hospital
    {
        int HospitalID;
        String HospitalName;
        Department[] AllDepartments;
        Address HospitalAddress;
        // Methods
        //Getters and setters
    }

---

Ask Questions?

---

## Composition: part-of

<!-- 
Daba 3ndna ka mital, human compose of brain،
Nhar kantzadou, kantzadou biih, 
So ila jab llah 9telna dak lhuman being, ghadi ymout m3ah ta lbrain, ou ila jab llah 7eyedna lmoukhlchi wa7ed rah may9derch y3ich, bla manjebdou chi nass bach mayt9el9ouch 3lina s7ab tik tok 
-->

---

![bg width:70%](comp_diag.png)

---

    class Department
    {
    int DeptID;
    String DeptName;
    int[] AllDoctors;
    int HospitalID;
    // Methods
    // Getters and Setters
    }
    
    class Hospital
    {
        int HospitalID;
        String HospitalName;
        Department department;
        Address HospitalAddress;
        // Methods
        //Getters and setters
        //Constructor
        Hospital(... , department,...){
            this.departement = departement
        }
    }

---

Ask Questions?

---

## Generalization/Specialization

---

![width: 500](generalization.png)

---

    class Animal extends Living{
        //tkherbi9
    }
    class Bird extends Living{
        //Tkherbi9 zayd
    }
    class Living{

    }

---

## Polymorphism

![bg right width:100%](polymorph_meme.jpeg)

<!-- 
Koul wa7ed ach mrebbi
Chi mchach chi klab chi 9rouda
Linfrid koul wa7ed fikoum mcha traina b l7ayaqan dyalou bach mli yguoul lih dwi, yguoul chi 7aja, 
Mli nji ana , makayhemnich achmen type l7ayawan dyalk, li kayhemni houwa mli nguoul lih dwi yguoul li chi 7aja,

Koulhoum 7ayawanat
Walaki Koul wa7ed kifach kayguoul liha

Kan9drou nwsslou liha b l inheritance w b abstraction

-->

---

    class Animal{
        // Atributes
        // getters and setters
        abstract String speak();
    }
    class Dog extends Animal{
        String speak(){
            return "Haw Haw";
        }
    }
    class Cat extends Animal{
        String speak(){
            return "Meow";
        }
    }
    class Sheep extends Animal{
        String speak(){
            return "ba333";
        }
    }
    class Test{
        public main(String *args){
            Animal micho = new Cat();
            Animal boby = new Dog();
            Animal chwa = new Sheep();
            micho.speak();
            boby.speak();
            chwa.speak();
        }
    }

---

## Association classes

---

![width:100%](association_classes.png)

---

## Diagram types

---

![bg width:80%](uml_types.png)

---

### Use Case Diagram

---

Provides an overview of functionality of the system or
business processes from a user perspective. The way in
which a user “uses” the system is the starting point for
creating a use case diagram.

---

![width:600](usecase_diag.png)

---

Ask Question?

---

### Activity Diagram

---

Models the flow anywhere in the system. In particular, the
flow within a use case describing normal user interactions
and the alternatives and exceptions is very well modeled by
these activity diagrams.

---

![width:500](activity_diagra.png)

---

Ask Question?

---

### State Machine : Etat Transition

---

Shows the runtime life cycle of an object in memory. Such a
life cycle includes all the states of an object and the
conditions under which the states change.

---

![width:500](state_diagram.png)

---

### Class Diagram

---

Represents classes, their definitions, and relationships.
Classes and entities from the problem space are
also detailed technical entities in the solution space.
The attributes and operations that define the classes
are included within this class diagram. Relationships in a
class diagram illustrate how classes interact, collaborate,
and inherit from other classes. Classes can also
represent relational tables, user interfaces, and
controllers.

---

![width:600](class_diag.png)

---

Ask Question?

---

### Objet Diagram

---

Shows objects and their links in the memory at runtime.
Therefore, these object diagrams also help visualize
multiplicities in practice.

---

![width:800](object_diag.png)

---

Ask Question?

---

### Sequence Diagrams

---

Models the interactions between objects based on their
timelines. Objects can be specifically shown on these
diagrams or they can be anonymous objects belonging to a
class. The sequence of execution of messages between
objects at runtime is well modeled by these diagrams,
hence their name.

---

![width:800](sequence_diag.png)

---

Ask Question?

![bg right width:100%](oop_end.jpeg)

---

<!-- this is a note -->

Reference:
Book: Software Engineering with UML
Link: https://www.geeksforgeeks.org/association-composition-aggregation-java/
