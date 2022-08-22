<template>
    <div className="about-container">
        <div className="about-text">
            <h4>Hi, my name is</h4>
            <h1>Mattias Gulec</h1>
            <hr />
            <p>
                I am freelance front-end developer from Stockholm, Sweden. I have
                experience in working in different areas of development, always
                trying to figure out the problems that comes with it and work
                towards a solution which pleases my client and myself. Though I have
                a strong focus on front-end development as well as React
                development, I can confidently say that nothing stops me from
                learning new things and trying to make the most out of my time.
            </p>
            <hr />
            <br />
            <p>
                I have a passion for learning and problem solving. I have worked
                with a variety of libraries and frameworks. I am currently looking
                for a position in the Front-End development industry.
            </p>
            <hr />
            <br />
            <p>
                I am a self-motivated individual who is always looking for new
                challenges and opportunities. I am a team player who is always
                willing to learn new skills and technologies.
            </p>
        </div>
    </div>
</template>

<style scoped>
.about-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    flex-wrap: wrap;
    margin: auto;
    padding: 50px 20px;
}

@media screen and (min-width: 768px) {
    .about-container {
        padding: 5% 20%;
    }
}

.about-text {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 100%;
    color: antiquewhite;

}

.about-text h4 {
    font-size: 1.5rem;
    margin: auto;
    text-align: center;
    padding: 5px;
}

.about-text h1 {
    font-size: 2rem;
    margin: auto;
    text-align: center;
    padding: 5px;
}

.about-text hr {
    width: 100%;
    margin: 10px 0px;
    border: 1px solid antiquewhite;
}

.about-text p {
    font-size: 1rem;
    margin: auto;
}
</style>