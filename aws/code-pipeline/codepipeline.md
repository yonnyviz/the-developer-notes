# AWS CodePipeline Notes

## What is AWS CodePipeline?

Is a **Continuous delivery service** that let us **model**, **visualize**, and **automate** the steps required to release software.

## What can I do with CodePipeline?

#### 1. Automate your release processes

- **Fully automates** your release process from end to end, starting from your **source repository through build, test, and deployment**.
- You can **prevent changes** from moving through a pipeline by including a **manual approval** action in any stage **except a Source stage**.
- You can **release when you want**, in **the way you want**, **on the systems of your choice**, **across one instance or multiple instances**.

#### 2. Establish a consistent release process

- Define a consistent set of steps for every code change.
- CodePipeline runs each stage of your release according to your criteria.

#### 3. Speed up delivery while improving quality

- Automate your release process to allow your developers to test and release code incrementally and **speed up the release of new features to your customers**.

#### 4. Use your favorite tools

- You can incorporate your existing source, build, and deployment tools into your pipeline.
- For a full list of AWS services and third-party tools currently supported by CodePipeline, see Product and service integrations with CodePipeline.

#### 5. View progress at a glance

- You can review **real-time status** of your pipelines.
- Check the details of any **alerts**.
- **Retry failed actions**.
- **View details about the source revisions** used in the latest pipeline execution in each stage.
- **Manually rerun** any pipeline.