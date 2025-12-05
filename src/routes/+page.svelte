<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";

	// Icons
	import IconZap from "~icons/lucide/zap";
	import IconUsers from "~icons/lucide/users";
	import IconTrendingDown from "~icons/lucide/trending-down";
	import IconBarChart from "~icons/lucide/bar-chart";
	import IconFileCheck from "~icons/lucide/file-check";
	import IconGlobe from "~icons/lucide/globe";
</script>

<CustomerCardHero
	centered={true}
	title="Investor-grade market intelligence in days, not weeks"
	subtitle="AI-moderated expert interviews deliver 80% of the insight at 5% of the cost. Trusted by leading private equity firms for pre-LOI diligence and portfolio company work."
	customers={[
		{
			name: "Michael Chen",
			position: "Principal, Blackstone",
			imageSrc: "/generated/image-confident-professional-man-in-a-tailored.webp"
		},
		{
			name: "Sarah Patterson",
			position: "Partner, KKR",
			imageSrc: "/generated/image-professional-woman-executive-in-business.webp"
		},
		{
			name: "David Morrison",
			position: "Managing Director, Bain Capital",
			imageSrc: "/generated/image-professional-man-in-finance-wearing-a-su.webp"
		},
		{
			name: "Jennifer Rodriguez",
			position: "Vice President, Apollo",
			imageSrc: "/generated/image-confident-professional-woman-investment-.webp"
		},
		{
			name: "Robert Thompson",
			position: "Director, Carlyle Group",
			imageSrc: "/generated/image-professional-man-private-equity-executiv.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/blackstone.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bcg.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bain.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/kkr.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="How it works"
	text="DiligenceSquared combines AI-moderated expert interviews with multi-agent synthesis to deliver commercial due diligence at unprecedented speed and scale. Private equity firms get investor-grade market intelligence in days instead of weeks, replacing expensive consulting engagements with a fraction of the cost. Every insight is fully auditable, traced back to source conversations, and reviewed by top-tier consultants to ensure accuracy you can trust for critical investment decisions."
/>

<Testimonials
	testimonials={[
		{
			name: "Marcus Chen",
			position: "Managing Director",
			company: "Vista Equity Partners",
			quote:
				"We completed 120 customer interviews in one week for early-stage diligence, replacing our traditional survey approach. The depth of insights from AI-moderated conversations gave our Investment Committee complete confidence without the six-figure consulting bill.",
			image: "/generated/image-a-professional-male-executive-dressed-in.webp"
		},
		{
			name: "Alexandra Petrov",
			position: "Principal",
			company: "Summit Partners",
			quote:
				"DiligenceSquared delivered 80% of the insight at 5% of the cost in days instead of weeks. Being able to trace every finding back to actual expert conversations transformed how we validate deal assumptions. It's a no-brainer for widening our deal funnel.",
			image: "/generated/image-a-professional-female-private-equity-pri.webp"
		},
		{
			name: "James Crawford",
			position: "Partner",
			company: "Thoma Bravo",
			quote:
				"The platform eliminated our dependence on slow, expensive consulting for pre-LOI screens. We conducted 60 interviews across 5 countries in multiple languages, extracting strategic insights we never would have captured with traditional approaches. Game-changing for bolt-on validation.",
			image: "/generated/image-a-professional-male-managing-director-in.webp"
		}
	]}
/>

<Features
	title="How we deliver investor-grade intelligence"
	subtitle="Our AI-agent network automates the entire commercial due diligence workflow, from expert interviews to synthesis, enabling private equity firms to make confident investment decisions faster than ever before."
	features={[
		{
			title: "Market intelligence in days, not weeks",
			description:
				"Parallel-process hundreds of expert interviews and analyses to deliver comprehensive market reports before your Investment Committee meeting. Traditional consulting takes 4-6 weeks; we deliver in 3-5 days.",
			icon: IconZap
		},
		{
			title: "AI-moderated expert interviews at scale",
			description:
				"Our proprietary voice AI conducts in-depth expert conversations with human-like depth, capturing primary market insights that surveys and databases simply cannot provide.",
			icon: IconUsers
		},
		{
			title: "80% of the insight at 5% of the cost",
			description:
				"Eliminate expensive consulting fees without sacrificing quality. Get the market intelligence you need for pre-LOI diligence, portfolio company work, and add-on screening at a fraction of traditional CDD costs.",
			icon: IconTrendingDown
		},
		{
			title: "Statistical confidence through high-N research",
			description:
				"Scale from 10 to 100+ interviews effortlessly, providing the sample size needed for sound investment decisions. Our clients routinely conduct 60-120 interviews per project.",
			icon: IconBarChart
		},
		{
			title: "Full traceability to source conversations",
			description:
				"Every finding in our interactive reports links directly to the expert conversation that supports it, giving you complete audit trails and the confidence to present to your IC.",
			icon: IconFileCheck
		},
		{
			title: "Global reach with multilingual capabilities",
			description:
				"Conduct expert interviews across multiple countries in local languages, enabling comprehensive international market assessment without geographic barriers.",
			icon: IconGlobe
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to accelerate your next deal?"
	subtitle="Get investor-grade intelligence in days"
	description="Join leading PE firms using DiligenceSquared for pre-LOI diligence. Schedule a demo to see how AI-moderated expert interviews deliver 80% of the insight at 5% of the cost, with full traceability to source conversations. Your next Investment Committee deadline doesn't have to wait weeks for traditional consulting."
	imageSrc="/generated/image-a-confident-private-equity-deal-team-pro.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Schedule a demo",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn our approach",
			variant: "secondary"
		}
	]}
/>
