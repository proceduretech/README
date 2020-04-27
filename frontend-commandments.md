# Ten commandments of frontend engineering

1. You shall have a component discussion with your peers before writing a single line of code. You shall explain what the component is supposed to do; explicitly mention the inputs, outputs and dependencies.
2. You shall give small PRs.
3. You shall start all components as functional & stateless. You shall use hooks extensively and also write your hooks if required.
4. You shall split the features in multiple PRs if it has many components. Each PR will have **only 1** component implemented (with or without API integration). It will have a storybook with stories of all states with dummy data.
5. You shall pay attention to the types. If a particular API doesn’t give data for a mandatory field then the field has to be made optional or a different class needs to be used which doesn’t have that mandatory field.
6. You shall write return types to all the API calls - even if it’s Promise<void>.
7. You shall attach screenshots of stories of that component in the PR.
8. You shall wire all the components together and integrate it with APIs only once you have implemented all the components.
9. You shall keep form validations in different files in the same sub directory. If the validation depend on some state or props, make it a method and pass the dependency.
10. You shall factor in additional time when estimating the feature.
