<!SLIDE title-slide>

# Hackathon Team 3 

## Classroom Training Deployments

### Team Members

`John Dohoney, Tyler Walker, Gonzalo Lopez, Roger Chao`

### Technologies

```Infrastructure: ie GCP, GKE, Terraform```

```Service Configuration and Service Discovery: Consul```

```Application: Front end portal + Showoff (OSS application) + Wetty```

### Business Case

Delivering classroom technical training requires travel to and from locations. This can be costly and also often requires students to download software that often does not involve the solution being taught. Attempts at fixing this problem are often one off solutions that don’t repeatability scale and lead to poor learning experience. This is a problem for online colleges, companies and partners delivering training solutions. 
Description
Team 3 plans to build a classroom training experience that enables teacher to repeatedly deploy training environments. This will eliminate the complexity and allow them to focus on delivering quality training for the students. 

The training solution will have a frontend student sign-up and will integrate with Terraform to provision the classroom. This will include the training application itself, which will  be running on K8s and backed by a repo which will serve the content for the class. Additionally, wetty containers to forward SSH sessions via browser to VMs that will have the needed tooling for student exercises. All of the K8s services will be registered with Consul and will run health checks across the class environment.

<!SLIDE bullets incremental transition=fade>

# Super Official Vault Training

![vault](vault.png)

## Agenda

## * Teach you Vault!
## * You will learn it!
## * You will like it!

<!SLIDE bullets>
# Student Create Secret


st=>start: Start:>http://www.google.com[blank]
e=>end:>http://www.google.com
op1=>operation: My Operation
sub1=>subroutine: My Subroutine
cond=>condition: Yes
or No?:>http://www.google.com
io=>inputoutput: catch something...
para=>parallel: parallel tasks

st->op1->cond
cond(yes)->io->e
cond(no)->para
para(path1, bottom)->sub1(right)->op1
para(path2, top)->op1

Andrew->China: Says Hello
Note right of China: China thinks\nabout it
China-->Andrew: How are you?
Andrew->>China: I am good thanks!

* Sometimes bullet items
  * Have sublists
  * And some sublist items
    * Have some of their own
    * And so on
* But top-level "bullet items" have no bullets
  * isn't that odd?

Also, sometimes you just want to have plain text sitting in the middle
of the screen. The quick brown fox jumps over the lazy dog.

<!SLIDE bullets incremental transition=fade>
# Sub bullets

* something
    * something else
* a third thing
    * and some more
    * inconsequential things
      * to fill up a sub bullet list
      * of things
* a fourth thing
* a fifth thing

<!SLIDE bullets>
# Third Slide

!SLIDE center transition=scrollUp
.notes another dark side

![octocat](octocat.png)
