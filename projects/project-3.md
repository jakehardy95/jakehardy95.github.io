---
layout: project
type: project
image: images/kahukailogo.png
title: Hawaii Annual Code Challenge 2021
permalink: projects/hacc
# All dates must be YYYY-MM-DD format!
date: 2021-10-23
labels:
  - React
  - Meteor
  - MongoDB
summary: My experience building an app for HACC
---

This year, a few of my classmates and I decided to participate in the Hawaii Annual Code Challenge (HACC) to get some experience building applications outside of the classroom. The HACC has around 5 challenges/applications that you can build and then they are judged. If you make it to the judging round, you can win up to $4000 for your team.

Our team chose to build the Hawaii Marine Animal Response Reporting and Sighting application, which we called Kahukai. To achieve this, we decided to use Meteor, React, MongoDB, and Semantic UI to build the app. Throughout the process, we learned a lot including notification pushing, form handling and submission, as well as user login and account creation. The biggest thing that I took away from this project is how great it is to work in teams and be able to accomplish a goal, especially through the resources that Github provides. 

Through the course of 3 months, we learned a lot in our Computer Science 314 class, Software Engineering. We applied what we learned in this class to building a full fledged web application that looks good on both browsers and smartphones.

This snippet was the landing page for our application. This didn't include the top menu but shows a glimpse at what we did for our application. Using Semantic UI React was very useful and made our app layout very easy to control and manipulate how we wanted to. If you would like to see more about this app, a link can be found [here](https://github.com/bloombugs)

If you would like to find a working version of the app, a link can be found [here](https://kahukai-bloombugs.cloud/#/)
```
<Container fluid>
        <Grid id='landing-page' className='center aligned'>
          <Grid.Row verticalAlign='middle'>
            <Grid.Column width={14}>
              <h3 className="intro">Welcome to Kahukai: the HMAR Reporting app</h3>
              <p>Select an option from below:</p>
              <Button as={NavLink} className="distressButton" exact to="/distress" color='red'>Animal in distress</Button>
              <Image src='https://www.mauibath.com/wp-content/uploads/2019/10/596998840197290025-300x300.png' size='small' centered className="logo"/>
              <Button as={NavLink} className="sightingButton" exact to="/sighting" color='blue'>Animal sighting</Button>
              <p className="clickHere">Don&apos;t know what an animal in distress looks like?</p>
              <Button as={NavLink} className="infoButton" exact to="/infodistress">Click here</Button>
            </Grid.Column>
          </Grid.Row>
        </Grid>
        <Container className='landingInfo'>
          <Grid className='center aligned'>
            <Grid.Row verticalAlign='middle'>
              <Grid.Column>
                <h1>Welcome to Kahukai: the HMAR Reporting app. This app is used to report animals in distress and to report
                  animal sightings so that Hawaii Marine Animal Respons(HMAR) can respond to and assess animals. </h1>
                <h4>To use this app, you can select from the following via the top menu: </h4>
                <List>
                  <List.Item>Distress Report: Prompts you to report an animal in distress to report to HMAR</List.Item>
                  <List.Item>Sighting Report: Prompts you to report an animal that you have sighted</List.Item>
                  <List.Item>Info: Provides information on what an animal in distress looks like.</List.Item>
                </List>
                <p>Clicking on the Kahukai Logo takes you back to this page.</p>
              </Grid.Column>
            </Grid.Row>
          </Grid>
        </Container>
</Container>
```
      
 

