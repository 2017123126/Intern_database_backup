# Material design - styles

Tags: UX design
관련 링크: https://m3.material.io/styles
상태: In progress
작성 일자: 2022년 11월 10일 오후 5:00

# Material design - styles

Styles are the visual aspects of a UI that give it a distinct look and feel. They can be customized by changing your Material theme.

# Motion

- Since transitions are the most common type of motion and are closely tied to usability, their design and implementation should be a top priority in your product.
- [Consider implementing a reduced motion setting](https://m3.material.io/m3/pages/motion-transitions/applying-transitions#107ca705-f145-4067-9005-278e57051515) to accommodate accessibility needs.

## Easing

In the physical world, objects don’t start or stop instantaneously. Instead, they take time to speed up and slow down. Therefore, motion with easing is meant to be natural.

[https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l3gg6j-01%20-%20Easing%20vs%20Linear%20-%203P.mp4?alt=media&token=7726fc49-a071-49ca-a660-fb6ca6f54941](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l3gg6j-01%20-%20Easing%20vs%20Linear%20-%203P.mp4?alt=media&token=7726fc49-a071-49ca-a660-fb6ca6f54941)

### [Emphasized easing set](https://m3.material.io/styles/motion/easing-and-duration/tokens-specs#cbea5c6e-7b0d-47a0-98c3-767080a38d95)

The **[Emphasized easing set](https://m3.material.io/styles/motion/easing-and-duration/tokens-specs#cbea5c6e-7b0d-47a0-98c3-767080a38d95)** is recommended for most transitions to capture the style of M3.

[Emphasized easing is used for this full screen transition.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl788zpqr-03%20-%20Emphasized%20easing%20-%203P.mp4?alt=media&token=01730d83-0e8f-463d-b082-d7247d4ba7ba)

Emphasized easing is used for this full screen transition.

[1. emphasized    2. emphasized decelerate    3. emphasized accelerate](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l3hrtr-01%20-%20Emphasized%20Easing%20Set.mp4?alt=media&token=1a52f0e6-dadd-43b8-9614-32ba9f19613c)

1. emphasized    2. emphasized decelerate    3. emphasized accelerate

### [Standard easing set](https://m3.material.io/styles/motion/easing-and-duration/tokens-specs#601d5552-a6e6-4d74-9886-ff8f24b9ec35)

The **[Standard easing set](https://m3.material.io/styles/motion/easing-and-duration/tokens-specs#601d5552-a6e6-4d74-9886-ff8f24b9ec35)** can be used for small utility focused transitions that need to be quick.

[Standard easing fits the simple utility of this component.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl788tbs7-04%20-%20Standard%20easing%20-%203P.mp4?alt=media&token=a8ee22db-a1bf-4bce-b51d-0c1c7f855041)

Standard easing fits the simple utility of this component.

[1. standard   2. standard decelerate    3. standard accelerate](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l3il7g-02%20-%20Standard%20Easing%20Set.mp4?alt=media&token=40a8a070-d197-431a-b176-8dc481866516)

1. standard   2. standard decelerate    3. standard accelerate

## Duration

- Transitions shouldn’t be jarringly fast or so slow that users feel as though they’re waiting
    
    [Avoid transitions with such a short duration they become jarring.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl789al8e-09%20-%20Duration%20-%20Dont%20-%203P.mp4?alt=media&token=1d0dd153-ee6e-4e3d-85b0-3657791d3563)
    
    Avoid transitions with such a short duration they become jarring.
    
- Choose a duration based on the transition size
    
    
    [Transitions that cover small areas of the screen have short durations](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l2ll2f-10%20-%20Small%20area%20-%203P.mp4?alt=media&token=3233cc48-7a8b-4ecd-b9d8-b654c5ffe01b)
    
    Transitions that cover small areas of the screen have short durations
    
    [Those that traverse large areas have long durations](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl789dv1c-11%20-%20Large%20area%20-%203P.mp4?alt=media&token=e93cd72d-8fab-446d-adbd-c0c927def9de)
    
    Those that traverse large areas have long durations
    
- Enter vs exit transitions
    
    [Transitions that exit, dismiss, or collapse an element use shorter durations because they require less attention than the user’s next task.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl788wgsy-12%20-%20Enter%20Exit%20-%203P.mp4?alt=media&token=b0cf4c78-7422-4d85-9706-23a5883c09d7)
    
    Transitions that exit, dismiss, or collapse an element use shorter durations because they require less attention than the user’s next task.
    
    [Transitions that enter or remain persistent on the screen use longer durations](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l2nwx9-13%20-%20Enter%20Exit%20-%203P.mp4?alt=media&token=cbc2a8c1-7389-4485-8f66-17b0c9090a8c)
    
    Transitions that enter or remain persistent on the screen use longer durations
    

## Transitions

Transitions are short animations that connect individual elements or full-screen views of an app. 

### Container transform

This pattern is used to seamlessly transform an element to show more detail, like a card expanding into a details page.

[A container transform is used when opening an app and a card. This makes the relationship between screens clear and gives an expressive quality to the transition.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl78agsqx-02%20-%20Container%20transform%20-%203P.mp4?alt=media&token=e11c41fb-8a53-4af9-8e62-497705fa372d)

A container transform is used when opening an app and a card. This makes the relationship between screens clear and gives an expressive quality to the transition.

[A container transform is used on an expanding sheet.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl7995kyy-08%20-%20Container%20transform%20-%20Sheet%20-%203P.mp4?alt=media&token=88995b98-6087-4b0f-8a52-9bfa96b49a7c)

A container transform is used on an expanding sheet.

[This container transform FAB transition has a persistent container and icon.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl7995dnx-07%20-%20Container%20transform%20-%20FAB%20-%203P.mp4?alt=media&token=f1f89c9f-0fcf-42ba-a8f5-3995e1f8d69d)

This container transform FAB transition has a persistent container and icon.

[Don't use container transform in apps with deep hierarchies, the motion becomes excessive. The expressive style also doesn't fit this utility focused navigation.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79ctf5l-17%20-%20Container%20Transform%20-%20Settings%20-%20Dont%20-%203P.mp4?alt=media&token=7d473bae-40e8-426c-9a8f-07b667a4d50b)

Don't use container transform in apps with deep hierarchies, the motion becomes excessive. The expressive style also doesn't fit this utility focused navigation.

### **Forward and backward**

This pattern is used for navigating between screens at consecutive levels of hierarchy, like navigating from an inbox to a message thread. 

[**Android** uses a fade as screens slide, whereas **iOS** uses a parallax effect, meaning the background slides slower than the foreground](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl799pzsl-09%20-%20Forward%20and%20backward%20-%203P.mp4?alt=media&token=9fa97074-51bf-48bc-a4c9-1ce9f8e779b1)

**Android** uses a fade as screens slide, whereas **iOS** uses a parallax effect, meaning the background slides slower than the foreground

[A card on iOS uses a forward and backward transition.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl799tv28-11%20-%20Forward%20and%20backward%20-%20Card%20-%203P.mp4?alt=media&token=3a4d5dbc-70f7-4458-a6db-29f3ccf16690)

A card on iOS uses a forward and backward transition.

[A search icon button in Android uses a forward and backward transition](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl799u98k-12%20-%20Forward%20and%20backward%20-%20Icon%20button%20-%203P.mp4?alt=media&token=fa3b3672-e4d4-4dd6-99a9-a40c15cc9fff)

A search icon button in Android uses a forward and backward transition

### **Lateral**

This pattern is used for navigating between peer content at the same level of hierarchy, like swiping between tabs of a content library. This also hints at being able to gesturally swipe elements to navigate.

[A lateral transition is used when tapping or swiping a tab component.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79a2qa9-14%20-%20Lateral%20-%20Tabs%20-%203P.mp4?alt=media&token=e2dd08f4-5306-4a94-a419-9f3cb51f9267)

A lateral transition is used when tapping or swiping a tab component.

[A lateral transition used with a carousel component.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79e6dp4-16%20-%20Lateral%20-%20Carousel%20-%203P.mp4?alt=media&token=01046d44-cfed-43a3-9b13-81b627838aa3)

A lateral transition used with a carousel component.

[A lateral transition should not be used for common forward and backward navigation as it results in an excessive amount of motion.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79cygzr-21%20-%20Forward%20Backward%20-%20Dont%20-%203P.mp4?alt=media&token=00de204d-7aab-4929-ba2b-85505ff4601d)

A lateral transition should not be used for common forward and backward navigation as it results in an excessive amount of motion.

### **Top level**

The exiting screen quickly fades out and then the entering screen fades in.

[A navigation bar uses a top level transition.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79adkur-17%20-%20Top%20Level%20-%20Navigation%20bar%20-%20Fade%20-%203P.mp4?alt=media&token=c273e894-f1f9-47ca-b73d-f0bb847d0dd3)

A navigation bar uses a top level transition.

[Don't use a lateral transition to move between top level destinations. The gesture conflicts with carousel and list item gestures.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79d068s-25%20-%20Top%20level%20-%20Dont%202.mp4?alt=media&token=11f7f14b-2657-4f0e-a5ea-b237816ece11)

Don't use a lateral transition to move between top level destinations. The gesture conflicts with carousel and list item gestures.

### **Enter and exit**

This pattern is used to introduce or remove a component on the screen. 

- **Within screen bounds**
    
    
    [A menu at the top of the screen expands downwards as it enters.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79au0ej-21%20-%20Enter%20and%20Exit%20-%20Menu%202%20-%203P.mp4?alt=media&token=162920df-0f29-4223-a2c6-f86f03fd4bba)
    
    A menu at the top of the screen expands downwards as it enters.
    
    [A snackbar and FAB use an enter and exit transition.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79auaco-22%20-%20Enter%20and%20Exit%20-%20FAB%20%26%20Snackbar%20-%203P.mp4?alt=media&token=bdd9f831-e87c-4040-b258-5025ac6ae89c)
    
    A snackbar and FAB use an enter and exit transition.
    
- beyond screen bounds
    
    
    [**Android** components expand and collapse along the x or y axis as they enter and exit. **iOS** components uniformly scale as they enter and fade out to exit.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79atp9a-20%20-%20Enter%20and%20Exit%20-%20Within%20bounds%20-%203P.mp4?alt=media&token=76026e78-8aba-4b5c-a2af-dfbb2d888313)
    
    **Android** components expand and collapse along the x or y axis as they enter and exit. **iOS** components uniformly scale as they enter and fade out to exit.
    
    [The direction of enter and exit transitions help establish a coherent spatial model.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79axbqr-27%20-%20Enter%20and%20Exit%20-%20Full%20frame%20-%20Across%20Bounds%20-%203P.mp4?alt=media&token=4068eb2e-f97a-49fa-b4cd-6b353187a225)
    
    The direction of enter and exit transitions help establish a coherent spatial model.
    
    [A navigation bar slides off and on screen during a scroll.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79awx69-26%20-%20Enter%20and%20Exit%20-%20Nav%20bar%20-%203P.mp4?alt=media&token=8643a39d-d591-43d8-81c4-1d0297ce305c)
    
    A navigation bar slides off and on screen during a scroll.
    
    [A top app bar slides off and on screen during a scroll.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79awkwm-25%20-%20Enter%20and%20Exit%20-%20Top%20App%20Bar%20-%203P.mp4?alt=media&token=9a4ef451-3ca3-4bc4-b3d9-fa53643dd01e)
    
    A top app bar slides off and on screen during a scroll.
    

[This bottom sheet uses an enter and exit transition pattern.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79d48wb-26%20-%20Enter%20Exit%20-%20Do%20-%203P.mp4?alt=media&token=0b4b222e-8358-40dc-a081-a9b5ec2c3840)

This bottom sheet uses an enter and exit transition pattern.

[Don't use an enter and exit pattern for navigating hierarchical screens.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79d0uk5-27%20-%20Enter%20exit%20-%20Dont%20-%203P.mp4?alt=media&token=48e4b28a-8d0c-4009-8d2a-2338aeefad84)

Don't use an enter and exit pattern for navigating hierarchical screens.

### **Skeleton loaders**

This pattern is used to transition from a temporary loading state to a fully loaded UI.

[A pulsing animation indicates indeterminant loading.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l9nbj8-29%20-%20Skeleton%20loader%20-%203P.mp4?alt=media&token=6c616d0b-70f9-42f6-a914-c6abe2ef5ed3)

A pulsing animation indicates indeterminant loading.

[Content quickly fades in once it's loaded.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl6l9lpan-30%20-%20Skeleton%20loader%20-%20Fade%20-%203P.mp4?alt=media&token=c3f401e3-aee6-47b3-8894-1965121db5b1)

Content quickly fades in once it's loaded.

### Dos and Don’ts

[Common transitions should not use overt style effects like bouncy springs.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79c64kt-15%20-%20Style%20-%20Dont%20-%203P.mp4?alt=media&token=6ae10387-e6e5-46bf-8537-fbb6c989f2c6)

Common transitions should not use overt style effects like bouncy springs.

[Avoid showing cross faded content, the overlap of partially transparent elements can result in messy and distracting frames.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79c4yhj-12%20-%20Fade%20-%20Dont%20-%203P.mp4?alt=media&token=424849a6-8a00-49ba-848e-4ba8fc4c4c67)

Avoid showing cross faded content, the overlap of partially transparent elements can result in messy and distracting frames.

[This transition has a simple vertical motion that’s easy to follow.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79c3ly5-09%20-%20Direction%20-%20Do%20-%203P.mp4?alt=media&token=48da64dd-cc78-40bc-acb8-010efd582e3f)

This transition has a simple vertical motion that’s easy to follow.

[Don’t animate many persistent elements independently. The various moving parts are distracting.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79c41b3-10%20-%20Direction%20-%20Dont%20-%203P.mp4?alt=media&token=62981806-d90a-4bfa-94f8-4ca0e589c473)

Don’t animate many persistent elements independently. The various moving parts are distracting.

[Content should not pop in and shift locations during a transition
[](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79dxewc-08%20-%20Spatial%20model%20-%20Dont%20-%203P.mp4?alt=media&token=9f22d1e0-eb55-4f84-abdb-80aff47c0553)](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79c1q42-04%20-%20Stable%20Layouts%20-%20Dont%20-%203P.mp4?alt=media&token=e7118780-82a2-46c7-a3a0-22aef5bea25c)

Content should not pop in and shift locations during a transition
[](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79dxewc-08%20-%20Spatial%20model%20-%20Dont%20-%203P.mp4?alt=media&token=9f22d1e0-eb55-4f84-abdb-80aff47c0553)

[Switching between horizontal and vertical carousel layouts creates a confusing spatial model.](https://firebasestorage.googleapis.com/v0/b/design-spec/o/projects%2Fm3%2Fimages%2Fl79dxewc-08%20-%20Spatial%20model%20-%20Dont%20-%203P.mp4?alt=media&token=9f22d1e0-eb55-4f84-abdb-80aff47c0553)

Switching between horizontal and vertical carousel layouts creates a confusing spatial model.