# Synesis sport: Frontend developer (ChatEG 💯💬📵🚀🤑)

[Послать резюме](mailto:jobs+js.chatEG@synesis.ru?subject=Мне%20интересна%20Ваша%20вакансия:%20JS%20Frontend%20разработчик)


```js
import React, {PureComponent} from 'react';

class NewJsDeveloper extends PureComponent {
    project = 'ChatEG';
    state = {
        thingsYouWillDevelop: {
            webChat: true,
            bots: true,
            p2pCalls: true,
            botMarkets: true
        }
    };

    wantToWorkHard = () => {
        // TODO: Check if candidate want to be part of amazing team
    };

    render() {
        return this.wantToWorkHard() ? <WelcomeOnBoard {...this.props}/> : null;
    }

    componentDidUpdate() {
        if (this.wantToWorkHard()) {
            console.log(`${this.project}: Welcome bro!`);
            console.log(`Lets help me with: ${Object.keys(this.state.thingsYouWillDevelop).join(',')}`);
            this.readMore();
        }
    }

    readMore = () => window.open('https://goo.gl/VKNEZn', 'Js Dev Vacancy');
}

NewJsDeveloper.defaultProps = {
    youKnow: {
        ecmaScript: 'ES6',
        viewLibrary: {name: 'React', version: 16},
        stateManagement: 'Redux with Thunk',
        buildEverythingWith: 'Webpack 4',
        stylesFramework: 'SASS'
    },
    niceToHave: {
        nodeJs: true,
        framework: {name: 'Koa.js', version: '2.0'},
        jsFormat: 'Typescript',
        testWith: ['Chai', 'Mocha'],
        cloud: 'Google Cloud'
    }
};

export default NewJsDeveloper;
```