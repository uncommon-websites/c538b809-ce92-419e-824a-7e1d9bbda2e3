<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Speed",
			description: "We help developers ship in days, not months. Progress over perfection, always."
		},
		{
			title: "Clarity",
			description: "Turning fuzzy app ideas into clear, actionable launch plans that actually work."
		},
		{
			title: "Community",
			description: "Empowering vibe coders and indie hackers to build profitable apps without limits."
		}
	];
</script>

<SecondaryHero
	title="We believe every developer deserves to ship"
	subtitle="Too many brilliant ideas die in endless AI coding loops. We exist to change that."
	imageSrc="/generated/image-a-group-of-modern-software-developers-co.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"It started with frustration—late nights wasted rewriting prompts, switching between AI coding tools, and watching promising app ideas stall out before they ever reached users. For solo developers and early-stage startup founders, the dream was simple: launch something useful, maybe even profitable. But too often, they hit the same wall—an endless cycle of code generation with no clear roadmap, no structure, and no traction. The constant loop of \"is this idea even worth building?\" became paralyzing. App after app sat half-finished in folders nobody opened again.",
		"App Canvas was born out of that exact pain. The goal wasn't to build just another AI tool. It was to create a real bridge—one that connects raw ideas to structured, profitable launches. The team realized that what developers actually needed wasn't more code—it was clarity. So they built a visual canvas that turned fuzzy app ideas into step-by-step launch plans in minutes, combining AI with business logic, validation flows, tool selection, and a growth-first mindset. Developers could finally skip the traditional bottlenecks like perfecting product specs or chasing the right stack—and just build.",
		"Now, thousands of indie hackers and solo builders are launching in days, not months. App Canvas is powering a wave of creators who value progress over perfection. It's becoming the go-to space for \"vibe coders\" to turn sparks of ideas into real, money-making apps with clarity and speed. And the vision goes further—democratizing app development across the $428 billion software market so that anyone with an idea and a drive to build can launch without limits."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Meet the team"
	subtitle="Former developers who lived the pain"
	stakeholders={[
		{
			name: "Jordan Kim",
			position: "Founder & CEO",
			bio: "Serial entrepreneur who spent too many nights stuck in AI coding loops before building App Canvas.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sam Rivera",
			position: "Head of Product",
			bio: "Former indie hacker who launched 3 apps the hard way before designing the visual canvas system.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Alex Chen",
			position: "Lead Engineer",
			bio: "AI specialist focused on building tools that actually help developers ship instead of just generate code.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<StakeholderGrid
	stakeholderType="investor"
	title="Backed by believers"
	subtitle="Investors who understand the developer experience"
	stakeholders={[
		{
			name: "Point Nine Capital",
			image: "https://cdn.brandfetch.io/pointnine.com/w/400/h/400/logo?c=1id_elLz2Bd5Ej-dWo7"
		},
		{
			name: "TSIC Ventures",
			image: "https://cdn.brandfetch.io/tiny.vc/w/400/h/400/logo?c=1a2b3c4d5e"
		},
		{
			name: "Sequoia Capital",
			image: "https://cdn.brandfetch.io/sequoiacap.com/w/400/h/400/logo"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to skip the loops?"
	subtitle="Join thousands of developers shipping faster"
	description="Stop getting stuck in AI coding limbo. Start turning your app ideas into profitable launches with the visual planning system that actually works."
/>
