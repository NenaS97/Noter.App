# Noter.App Guide

A guide for the fictional Noter.App note-taking application, designed to assist new users in understanding its core features and basic workflows.

## About This Project

This guide was developed using the Darwin Information Typing Architecture (DITA) standard. The content is authored in modular XML files, demonstrating the principles of information typing and topic-based authoring. The project showcases the use of concept, task, and reference topic types to deliver a comprehensive user onboarding experience.

**Note:** The content within this personal project was AI-generated for demonstration purposes.

## Technical Elements and Attributes Used

The DITA source files in this project utilize the following elements and attributes to structure and present information effectively:

**Topic Structure:**

* **`<topic>`:** The root element for conceptual information, used in the introduction.
* **`<title>`:** Used for the title of each topic, section, and other structural elements.
* **`<shortdesc>`:** Provides a brief description or summary of the topic's content.
* **`<conbody>`:** The main body content container within a `<concept>` topic, used for the introduction.
* **`<reference>`:** The root element for reference information, used for the interface overview.
* **`<refbody>`:** The main body content container within a `<reference>` topic.
* **`<task>`:** The root element for procedural information, used for installation, account login, note creation, task creation, and calendar navigation.
* **`<taskbody>`:** The main body content container within a `<task>` topic.

**Content Elements:**

* **`<p>`:** For standard paragraphs of text.
* **`<ul>`:** For unordered (bulleted) lists.
* **`<li>`:** For individual items within lists.
* **`<section>`:** To divide content within `<refbody>` into titled sections.
* **`<image>`:** To embed images, used in the interface overview.
* **`<alt>`:** Attribute used with `<image>` to provide alternative text for accessibility.

**Task-Specific Elements:**

* **`<prereq>`:** Specifies conditions that must be met before a task can be started.
* **`<steps>`:** Contains the ordered sequence of actions in a task.
* **`<step>`:** Represents a single action within a `<steps>` element.
* **`<substeps>`:** Provides a nested list of more detailed actions within a `<step>`.
* **`<cmd>`:** Specifies the action the user needs to perform within a `<step>`.
* **`<info>`:** Provides detailed information and context for a `<cmd>`.
* **`<result>`:** Describes the outcome of completing a `<step>` or the entire `<task>`.

**Linking Element:**

* **`<xref>`:** Creates cross-references to other parts of the documentation or external resources, utilizing the `href` attribute to specify the target and the `scope` attribute to indicate if the target is local or external.

The DITA source files were processed using the **DITA Open Toolkit (DITA-OT)** to generate a user-friendly HTML version of the guide.

## View the Guide

The generated HTML output of this guide can be found in the `outputs` directory after processing the DITA source files with DITA-OT.
