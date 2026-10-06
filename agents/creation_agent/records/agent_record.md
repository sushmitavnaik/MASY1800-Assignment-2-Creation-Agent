# Specialist Agent Record

- Repository / branch / commit:
  https://github.com/sushmitavnaik/MASY1800-Assignment-2-Creation-Agent.git / main / 7510d34

- Agent / assignment:
  Assignment 2 - Emerging Technology Creation Agent

- General ET finding:
  Generative AI and large language models emerged through the convergence of multiple prior capabilities rather than from a single invention. Important developments included Transformer architecture, large-scale generative pretraining, increasing model/data/compute scale, prompting and few-shot learning, and later instruction tuning and reinforcement learning from human feedback. These developments moved language models toward more general-purpose, instruction-responsive systems.

- Application finding:
  For an internal employee knowledge assistant, the creation history suggests that an LLM is most useful as a natural-language interpretation and synthesis layer rather than as an authoritative source of organizational policy. The evolution of retrieval-augmented generation is particularly relevant because it allows a language model to use controlled external knowledge sources instead of relying only on pretrained model knowledge.

- Organization-specific finding:
  For a large financial-services company with sensitive data, compliance obligations, legacy systems, and a conservative risk posture, the technology's inherited limitations make grounding, access control, source authority, provenance, and bounded use especially important. The general technology history does not change, but its implications become more cautious because incorrect or unsupported answers could create compliance, operational, or reputational consequences.

- Primary test result:
  The primary test produced a structurally valid response and clearly separated the general technology history from application-specific and organization-specific implications. It appropriately linked the history of LLM development to the proposed internal knowledge-assistant application and identified retrieval, grounding, and source control as particularly relevant in the financial-services context.

- Contrast result - what stayed stable:
  The contrast test preserved the same core creation story for Generative AI / Large Language Models. Both runs identified the importance of Transformer architecture, large-scale pretraining, increasing scale, prompting, and instruction-following or human-feedback techniques. This was appropriate because changing the application and organization should not rewrite the general technology history.

- Contrast result - what changed:
  The organization-specific interpretation changed appropriately. The financial-services case emphasized grounding, access controls, source authority, compliance consequences, and a tightly controlled pilot. The contrast case, involving supervised marketing ideation at a small consumer-goods company, supported a more reversible bounded experiment because drafts could be reviewed before publication and the consequences of errors were generally lower and more reversible.

- Weakness/failure found:
  Although the two runs preserved the same overall creation story, the exact historical emphasis and evidence set shifted more than necessary between the primary and contrast cases. Some historical milestones received more attention in one case than the other even though the emerging technology itself had not changed. The outputs also contained occasional stray prompt-related text such as "Pasted text," which reduced output cleanliness.

- Revision made:
  I revised the specialist instructions to require a substantially consistent core creation/evolution account whenever the emerging technology remains the same across cases unless genuinely new evidence is introduced. I also clarified that context-specific technologies or techniques may become more relevant to the application finding without displacing the stable general ET history. In addition, I added a testing rule requiring the agent to avoid reproducing prompt artifacts, placeholder text, or other stray text in the analytical response.

- Remaining limitation:
  The Creation Agent can explain the technology's origins, predecessor capabilities, enabling conditions, and contextual implications, but it cannot determine overall organizational readiness, financial feasibility, governance sufficiency, implementation readiness, diffusion, or the final go/no-go adoption decision. It also depends on credible external evidence for consequential historical and technical claims, and conflicting or incomplete evidence may require qualified conclusions.

- Independent judgment:
  The Creation Agent is credible enough for team consideration because it consistently distinguishes general technology history from application-specific and organization-specific implications, uses an explicit evidence policy, and respects its analytical boundary. The primary and contrast tests showed meaningful context sensitivity while preserving the underlying technology history. Its main remaining limitation is that strong historical analysis alone cannot determine whether an organization should ultimately adopt or deploy the technology.

- AI / verification note:
  ChatGPT was used to help interpret the assignment, draft and refine the specialist analytical instructions, structure the primary and contrast cases, generate test outputs, diagnose weaknesses, and support revision of the agent. Consequential historical and technical claims were expected to be supported by credible primary or authoritative sources rather than model memory alone. The scaffold's local integrity checker and response validator were used to verify that the frozen core remained intact and that the saved structured responses followed the required output contract.