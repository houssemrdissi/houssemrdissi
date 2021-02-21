### Hi there 👋

I'm Houssem Rdissi, I'm DevOps Intern at Linkfire :fire: <br>
Working remotely from Tunisia .

- 🔭 I’m currently working on my Internship project in order to succeed it and get my engineering diploma :mortar_board:
- 📫 How to reach me: https://www.linkedin.com/in/houssem-rdissi-9218b7182/

<?php

namespace AshBaker;

class About extends Me
{
    public function getCurrentWorkplace(): array
    {
        return [
            'workplace' => [
                'company' => 'Qquicker',
                'position' => 'Product Owner'         
            ]
        ];
    }

    public function getDailyKnowledge(): array
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            ReactNative::class,
            TailwindCss::class,
            Aws::class,
        ];
    }

    public function getFutureGoal(): string
    {
        return 'To contribute to open source.';
    }
}
