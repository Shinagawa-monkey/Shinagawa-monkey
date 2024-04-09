<div class="flex-container">
    <div class="content">
        <h1>Hi! My name is Elena Shatalova</h1>
        <h2>Full Stack Software Engineer</h2>
        <p>
            I'm a MERN stack software engineer with 3+ years of experience in backend and frontend development. I am working on some side projects, continuously learning new languages and technologies. Able and willing to think outside the box.
        </p>
        <ul>
            <li>🌍 I'm based in Playa del Carmen, Mexico</li>
            <li>✉️ You can contact me at <a href="mailto:elenashatalova.it@gmail.com">elenashatalova.it@gmail.com</a></li>
            <li>🚀 I'm currently working on <a href="https://khnm5-qiaaa-aaaap-aam6a-cai.ic0.app/">DeFi DApp DBANK on ICP using Motoko</a></li>
            <li>🧠 I'm learning Python; Data Structures and Algorithms</li>
            <li>🤝 I'm open to collaborating on Projects that will help me to expand my skill set and help me to grow in my current role.</li>
            <li>⚡ If you type 'Google' into Google, you can break the internet. So please, no one try it, even for a joke. (c)</li>
        </ul>
    </div>
    <img src="https://github.com/Shinagawa-monkey/Shinagawa-monkey/blob/main/octocat.png" class="image" width="256" />
</div>

.flex-container {
    display: flex;
    flex-wrap: wrap;
}

.content {
    flex: 1;
}

.image {
    align-self: flex-start;
}

@media only screen and (max-width: 600px) {
    .flex-container {
        flex-direction: column;
    }

    .image {
        order: -1;
    }
}
