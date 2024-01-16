---
layout: default
title: SpeechComposer
---

<div class="post">
	<h1 class="pageTitle">SpeechComposer: </h1>
	<h1 class="pageTitle">Unifying Multiple Speech Tasks with Prompt Composition</h1>
	<img src="{{ '/assets/img/arch.jpg' | relative_url }}" alt="">
	<p>Recent advancements in language models have significantly enhanced performance in multiple speech-related tasks. Existing speech language models typically utilize task-dependent prompt tokens to unify various speech tasks in a single model. However, this design omits the intrinsic connections between different speech tasks, which can potentially boost the performance of each task. In this work, we propose a novel decoder-only speech language model, SpeechComposer, that can unify common speech tasks by <i> composing a fixed set of prompt tokens</i>. Built upon four primary tasks -- speech synthesis, speech recognition, speech language modeling, and text language modeling -- SpeechComposer can easily extend to more speech tasks via compositions of well-designed prompt tokens, like voice conversion and speech enhancement. The unification of prompt tokens also makes it possible for knowledge sharing among different speech tasks in a more structured manner. Experimental results demonstrate that our proposed SpeechComposer can improve the performance of both primary tasks and composite tasks, showing the effectiveness of the shared prompt tokens. Remarkably, the unified decoder-only model achieves a comparable and even better performance than the baselines which are expert models designed for single tasks.</p>
</div>
