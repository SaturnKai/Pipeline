<script lang="ts">
	import BenefitsSection from "components/BenefitsSection.svelte";
	import Courses from "./Courses.svelte";
	import Hero from "components/Hero.svelte";
	import TextSection from "components/TextSection.svelte";
	import Certifications from "./Certifications.svelte";
	import Team from "./Team.svelte";

</script>

<svelte:head>
	<title>Program Information | IT Workforce Pipeline</title>
</svelte:head>

<Hero title="Program Information" image="/assets/img/about.png">
    This program offers a dynamic blend<br> of online and in-person learning<br> experiences designed to equip students<br> with essential technical skills and<br> industry recognized certifications.
</Hero>

<TextSection title="What does this program cover?">
    This program spans two college courses: CS135 (Computer Science) in the fall and EDW135 (Employability Skills) in the spring. Additionally, participants engage in three IT workshop series covering topics such as Introduction to Cybersecurity, Introduction to Cloud Computing, and Web Design and Internet Computing. The program culminates in an industry certification exam series facilitated by guest speakers.
    <br>
    <br>
    Additionally, participants engage in three IT workshop series covering topics such as Introduction to Cybersecurity, Introduction to Cloud Computing, and Web Design and Internet Computing. The program culminates in an industry certification exam series facilitated by guest speakers.
</TextSection>

<Courses></Courses>

<TextSection title="Certifications Available">
    Upon successful completion, students earn one of several sought-after industry credentials, including AWS Certified Cloud Practitioner, CompTIA IT Fundamentals (ITF+), CompTIA A+, CompTIA Cloud+, CompTIA Network+, or CompTIA Security+. These stackable credentials and earned college course credits contribute toward a Bachelor's degree in Computer Science, Information Technology, or Cybersecurity at UNLV.
</TextSection>

<Certifications></Certifications>

<TextSection title="Summer Internship">
    The program also includes a rewarding summer paid internship opportunity. Industry partners sponsor up to 10 weeks of full-time paid internships at a rate of $15+ per hour. Moreover, completion of the program guarantees job interviews for all participating students.
</TextSection>

<BenefitsSection></BenefitsSection>

<Team></Team>