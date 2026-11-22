<div align="center">

<a href="https://lmspeed.net"><img src="https://raw.githubusercontent.com/LMSpeed/.github/main/profile/assets/logo-square.png" width="96" height="96" alt="LMSpeed" /></a>

# LMSpeed

**Measure the momentum of intelligence.**

Independent LLM API benchmarks, model comparisons and evidence-based endpoint audits.

[Website](https://lmspeed.net) · [Compare APIs](https://lmspeed.net/speed) · [Try Audit](https://lmspeed.net/audit) · [Documentation](https://docs.lmspeed.net)

**English** · [简体中文](https://github.com/LMSpeed/.github/blob/main/profile/README.zh-CN.md) · [Русский](https://github.com/LMSpeed/.github/blob/main/profile/README.ru.md)

</div>

## Choose with evidence

LMSpeed makes a fast-moving model landscape easier to navigate. We measure API performance, organize model and provider information, and build open tools that help developers inspect the services they depend on.

- **Compare performance:** first-token latency, throughput, availability and API speed.
- **Explore models and providers:** specifications, capabilities, published pricing and provider options.
- **Check endpoint behavior:** streaming, tool calling, structured output, prompt isolation, context recall and calibrated fingerprint evidence.

## Open projects

| Project | What it offers | Get started |
| --- | --- | --- |
| [Audit](https://github.com/LMSpeed/Audit) | 26 modular probes for LLM API and relay contracts, with a CLI and SDK. Supports OpenAI Chat/Responses and Anthropic Messages. | [Run online](https://lmspeed.net/audit) · [Install](https://github.com/LMSpeed/Audit#installation) · [npm](https://www.npmjs.com/package/@lmspeed/audit) |
| [models](https://github.com/LMSpeed/models) | An open, source-attributed model specifications project. **In preparation**; the repository does not yet contain a published dataset. | [Browse the current model catalog](https://lmspeed.net/model) |

For a one-off local audit, start with the published command's help:

```sh
pnpm dlx @lmspeed/audit --help
```

## Explore LMSpeed

| Resource | What you can do |
| --- | --- |
| [API speed test](https://lmspeed.net/speed) | Measure an endpoint's response performance. |
| [Model catalog](https://lmspeed.net/model) | Compare model specifications and capabilities. |
| [Provider directory](https://lmspeed.net/provider) | Explore API providers and their offerings. |
| [Online Audit](https://lmspeed.net/audit) | Run endpoint checks and share the resulting report. |
| [Free API keys](https://lmspeed.net/free-api-keys) | Find available provider offers for trying APIs. |
| [Documentation](https://docs.lmspeed.net) | Read product and integration guides. |

## How we report results

Observations, execution coverage and conclusions belong together. An unsupported capability or a blocked request is not a passing check. A behavioral fingerprint or header hint does not authenticate the true upstream model, and a clean audit applies only to the workload tested. See [Audit's methodology](https://github.com/LMSpeed/Audit#methodology--evidence-boundaries).

## Contribute and get in touch

- **Audit bugs and feature requests:** [open an issue](https://github.com/LMSpeed/Audit/issues). Include the version, protocol, expected result and a redacted reproduction.
- **Website feedback and general inquiries:** email [team@lmspeed.net](mailto:team@lmspeed.net).
- **Updates from the maintainer:** [@nexmoe on X](https://x.com/nexmoe).

Please remove API keys, credentials and private endpoint details before posting an issue or report. Follow each repository's contribution and licensing information.
