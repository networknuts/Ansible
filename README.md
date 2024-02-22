<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://networknuts.net">
    <img src="https://networknuts.net/wp-content/uploads/2019/11/nnlogosmall.png" alt="Logo" width="80" height="80">
  </a>

# Ansible

Some sample playbooks for Ansible Course 

http://networknuts.net

## Usage

### Use this to execute an ad-hoc command.

```bash
ansible hostname -m modulename -a 'arguments'
```

### Use the syntax-check command to check syntax in a playbook.

```bash
ansible-playbook *playbookname.yml* --syntax-check
```

### Use this to execute a playbook.

```bash
ansible-playbook *playbookname.yml*
```

### Use this check ansible documentation for a module.

```bash
ansible-doc *modulename*
```

## Chapter 2: Introduction to Playbooks
This introduces you to the world of Ansible playbooks. Here you will find playbooks for basic tasks.

## Chapter 3: Multiple Plays
This chapter contains playbooks with multiple plays inside of them. It illustrates how to use playbooks effectively.

## Chapter 4: Variables in Ansible
This chapter focuses on making our code reusable in different situations by using the concepts of variables.

## Chapter 5: Loops in Ansible
In this chapter, we see playbooks where loops are being used to minimize duplication of tasks.

## Chapter 6: Conditions in Ansible
Ansible conditions teach us how to adapt our playbooks to different conditions such as only running plays when certain conditions are true.

## Chapter 7: Ansible Handlers
This chapter shows how to use Ansible Handlers to only perform certain tasks when needed.

## Chapter 8: Task Failure Handling
Task Failure or a failure in our Playbooks will happen. This chapter shows us how to handle errors in our Playbooks.

## Chapter 9: Templating in Ansible
Creating custom files depending upon the environment is important, playbooks in this chapter shows us how to do so using the Ansible Templating Engine known as Jinja2.
