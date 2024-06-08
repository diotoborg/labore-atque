# @diotoborg/labore-atque
[![lint](https://github.com/diotoborg/labore-atque/actions/workflows/lint.yaml/badge.svg)](https://github.com/diotoborg/labore-atque/actions/workflows/lint.yaml)
[![test](https://github.com/diotoborg/labore-atque/actions/workflows/test.yaml/badge.svg)](https://github.com/diotoborg/labore-atque/actions/workflows/test.yaml)
[![npm version](https://img.shields.io/npm/v/@diotoborg/labore-atque)](https://www.npmjs.com/package/@diotoborg/labore-atque)
[![npm downloads](https://img.shields.io/npm/dw/@diotoborg/labore-atque)](https://www.npmjs.com/package/@diotoborg/labore-atque)
[![license](https://img.shields.io/npm/l/@diotoborg/labore-atque)](https://github.com/diotoborg/labore-atque/blob/main/LICENSE)

Run [BDD](https://cucumber.io/docs/bdd/) tests with [Playwright](https://playwright.dev/) runner.

> Inspired by the issue in the Playwright repo [microsoft/playwright#11975](https://github.com/microsoft/playwright/issues/11975)

> [!TIP]
> Playwright-bdd **v6** is out! Check out [Cucumber reporters](https://vitalets.github.io/@diotoborg/labore-atque/#/reporters/cucumber) and share your feedback 

## Why Playwright runner?
Both [Playwright](https://playwright.dev/) and [CucumberJS](https://github.com/cucumber/cucumber-js) have their own test runners. 
You can use CucumberJS runner with [Playwright as a library](https://medium.com/@manabie/how-to-use-playwright-in-cucumberjs-f8ee5b89bccc) to test BDD scenarios.
This package offers **an alternative way**: convert BDD scenarios into Playwright tests and run them with Playwright runner as usual. 
Such approach brings all the benefits of Playwright runner:

* Automatic browser initialization and cleanup
* Auto-capture of screenshots, videos and traces
* Parallelization with sharding
* Auto-waiting of page elements
* Out-of-box visual comparison testing
* Power of Playwright fixtures
* [...a lot more](https://playwright.dev/docs/library#key-differences)

## Extras
Some features were developed in `@diotoborg/labore-atque` on top of Playwright and BDD approaches:

* [Decorator steps](https://vitalets.github.io/@diotoborg/labore-atque/#/writing-steps/decorators)
* [Special tags](https://vitalets.github.io/@diotoborg/labore-atque/#/writing-features/special-tags)
* [Calling step from step](https://vitalets.github.io/@diotoborg/labore-atque/#/writing-steps/playwright-style?id=call-step-from-step)

## Documentation
Check out [documentation website](https://vitalets.github.io/@diotoborg/labore-atque/#/).

## Example
Fork and play with [@diotoborg/labore-atque-example](https://github.com/diotoborg/labore-atque-example) repo.

## Feedback
Feel free to share your feedback in [issues](https://github.com/diotoborg/labore-atque/issues).

## Changelog
Inspect the latest changes in the [CHANGELOG.md](https://vitalets.github.io/@diotoborg/labore-atque/#/changelog).

## Contributing
Your contributions are welcome! Review [DEVELOPMENT.md](https://github.com/diotoborg/labore-atque/blob/main/DEVELOPMENT.md) for @diotoborg/labore-atque local setup and development.

## Sponsors
Great thanks to the sponsors for supporting @diotoborg/labore-atque project ❤️ [Become a sponsor](https://github.com/sponsors/vitalets)

<!-- sponsors --><a href="https://github.com/currents-dev"><img src="https://github.com/currents-dev.png" width="60px" alt="Currents.dev" /></a><a href="https://github.com/jzaratei"><img src="https://github.com/jzaratei.png" width="60px" alt="" /></a><a href="https://github.com/NikkTod"><img src="https://github.com/NikkTod.png" width="60px" alt="" /></a><a href="https://github.com/alescinskis"><img src="https://github.com/alescinskis.png" width="60px" alt="Arturs Leščinskis" /></a><a href="https://github.com/kahuna227"><img src="https://github.com/kahuna227.png" width="60px" alt="" /></a><a href="https://github.com/alexhvastovich"><img src="https://github.com/alexhvastovich.png" width="60px" alt="" /></a><!-- sponsors -->

## How to make BDD valuable for my project?

Have a look on [this section](https://vitalets.github.io/@diotoborg/labore-atque/#/faq?id=how-to-make-bdd-valuable-for-my-project).

## License
[MIT](https://github.com/diotoborg/labore-atque/blob/main/LICENSE)