<script lang="ts">
	import { Presentation } from '@components'
	import IntroSlide from './slides/intro-slide.svelte'
	import Definition from './slides/definition.svelte'
	import DefinitionFake from './slides/definition-fake.svelte'
	import Continue from './slides/continue.svelte'
	import VersionControl from './slides/version-control.svelte'
	import Reviews from './slides/reviews.svelte'
	import LearnTheBasics from './slides/learn-the-basics.svelte'
	import AskQuestions from './slides/ask-questions.svelte'
	import Gameplan from './slides/gameplan.svelte'
	import Documentation from './slides/documentation.svelte'
	import Accessibility from './slides/accessibility.svelte'
	import Framework from './slides/framework.svelte'
	import Colab from './slides/colab.svelte'
	import Test from './slides/test.svelte'
	import OutroSlide from './slides/outro-slide.svelte'
</script>

<Presentation>
	<IntroSlide />
	<DefinitionFake />
	<Definition />
	<Continue />
	<VersionControl />
	<Reviews />
	<LearnTheBasics />
	<AskQuestions />
	<Gameplan />
	<Documentation />
	<Accessibility />
	<Framework />
	<Colab />
	<Test />
	<OutroSlide />
</Presentation>
