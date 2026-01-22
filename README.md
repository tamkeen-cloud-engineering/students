# Students

![screenshot](./images/screenshot.png)

## Objectives

The objectives of this exercise is for you to learn:

- the difference between forking and cloning a repository,
- stage, commit, and push your changes,
- create a pull request to merge your changes to the upstream repository, and
- how to deal with merge conflicts.

## Fork and clone the repository

![fork](./images/fork.png)

Fork this repository on GitHub. This will create a copy on your GitHub account that you can edit. Make sure to uncheck "Copy `main` branch only" so that you fork all the branches. We want to also get the `students` branch from this repository.

Now, clone your own copy to your local machine to make changes.

```sh
git clone https://github.com/tamkeen-cloud-engineering/students.git
```

## Add your name and details

Edit the `students.json` file in the `data` folder and add your name and details.

```json
{ 
  "name": "Your Name Here",
  "cohort": 2,
  "photo": "https://your-photo-here.com",
}
```

## Stage, commit, and push

Stage, commit, and push your changes to your remote repository on GitHub.

```sh
git add students.json
git commit -m "Add new student"
git push origin main
```

## Create a pull request

Create a pull request on GitHub to merge your changes to the upstream repository. Learn more about [creating pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).

## Add an image to your profile card

If you have an image hosted on the web, you can add it to your profile card. Otherwise a default image will be used. You can also generate your own avatar with [DiceBear](https://www.dicebear.com/).

![example](./images/example.png)
