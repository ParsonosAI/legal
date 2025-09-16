# Third Party APIs and Subprocessors

The following table provides an overview of our subprocessor and the APIs we use to provide our services. Each entry has the relevant privacy policy, terms of service and/or data processing agreements linked, where applicable.

| Subprocessor | Purpose | Extend of data access | Security Measures / Data Processing |
| --- | --- | --- | --- |
| Gemini | Generate text responses to prompts | Significant pieces of provided scripts for processing purposes. Provided autio. (no retention, no training) | (Privacy Policy (paid services))[https://ai.google.dev/gemini-api/terms#paid-services] |
| Stripe | Payment processing & account handling | Name & Email & Address as well as payment information (not visible to us) | (Data Processing Agreement)[https://stripe.com/en-gb-de/legal/dpa] |
| AssemblyAI | Transcription | Full Audio (no retention, no training) | (Privacy Policy)[https://www.assemblyai.com/legal/privacy-policy] |
| Speechmatics | Transcription | Small bits of Audio (few seconds, no retention, no training) | (Privacy Policy)[https://www.speechmatics.com/legal/privacy-policy] |
| PostHog | Analytics | IP Address, User Agent, Page Visits, Events | (Privacy Policy)[https://posthog.com/privacy] |
| Convex | Database | Metadata storage for our service | (Privacy Policy)[https://www.convex.dev/legal/privacy/v2024-03-21] |

# Data Processing and Retention

Wherever possible, we opted for processing project data in a way that does not require storing it. For example, we use AssemblyAI for transcription, which processes the audio and returns the text without storing the audio. We also use Speechmatics for transcription, which processes small bits of audio (a few seconds) and does not store the audio.
