<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Plan faster. Launch sooner."
	subtitle="Build real apps without getting stuck in loops."
	imageSrc="/generated/image-a-solo-developer-working-at-a-modern-des.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by developers worldwide" 
	logoUrls={[
		'https://cdn.brandfetch.io/replit.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/linear.app/w/400/h/400/logo',
		'https://cdn.brandfetch.io/vercel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	generating
	testimonials={[
		{
			name: "Jane Smith",
			position: "CTO",
			company: "Tech Innovations",
			quote:
				"Their cutting-edge automation boosted our productivity by 35%.\nThe intuitive interface reduced training time and improved team adoption.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "John Doe",
			position: "Director of Operations",
			company: "Global Solutions",
			quote:
				"Their robust security protocols gave us confidence in handling sensitive data.\nThe 24/7 support team resolved issues within hours, not days.",
			image: "https://www.unc.mn/image-placeholder.svg"
		},
		{
			name: "Sarah Johnson",
			position: "Product Manager",
			company: "Future Systems",
			quote:
				"The scalable platform grew seamlessly with our business needs.\nTheir customization options allowed us to tailor solutions perfectly to our workflows.",
			image: "https://www.unc.mn/image-placeholder.svg"
		}
	]}
/>

<Features
	title="Skip the loops, ship the product"
	subtitle="Visual planning that eliminates AI coding frustration and accelerates your path to profitable apps"
	features={[
		{
			title: "Visual canvas planning",
			description: "Map your entire app journey on an intuitive visual canvas that eliminates planning paralysis and keeps you focused on what matters.",
			imageSrc: "/generated/image-a-team-of-people-gathered-around-a-large.webp"
		},
		{
			title: "AI-powered validation",
			description: "Get instant validation frameworks and market insights before you write a single line of code, reducing the risk of building apps nobody wants.",
			imageSrc: "/generated/image-a-group-of-professionals-in-an-office-en.webp"
		},
		{
			title: "Smart AI prompts",
			description: "Receive perfectly crafted prompts for each development step that work seamlessly with tools like Lovable and Bolt.",
			imageSrc: "/generated/image-a-developer-working-at-a-desk-with-noteb.webp"
		},
		{
			title: "Instant tech stack",
			description: "Get AI-generated technology recommendations tailored to your specific app idea and target market in seconds.",
			imageSrc: "/generated/image-a-group-of-people-outside-energetically-.webp"
		},
		{
			title: "Growth strategy",
			description: "Launch with a complete customer acquisition roadmap that turns your MVP into a money-making business from day one.",
			imageSrc: "/generated/image-several-colleagues-gathered-around-a-tab.webp"
		},
		{
			title: "Progress tracking",
			description: "Monitor your development journey with visual milestones that keep you motivated and on track to launch.",
			imageSrc: "/generated/image-a-team-celebrating-progress-by-placing-m.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
