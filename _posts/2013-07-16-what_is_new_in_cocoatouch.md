---
layout: post
title: What's new in cocoatouch
---

#What's new in cocoatouch

##Multitasking

###background fetching 

####New delegate method on UIApplication is called



####Tuning the fetch interval


















### Tint
####New UIView property
	@property (nonatomic, retain)UIColor *tintColor;

####Dimming adjustment behavior
#### Finding out about changes
	-(void) tintColorDidChange;
###View Animation
#### No animations
	+(void)perforWithoutAnimation:(void(^)(void))actionsWithOutAnimation;
#### Keyframes

	+ (void)animateKeyframesWithDuration:(NSTimeInterval)duration










Abstract superclass

	 - (NSDictionary *)keyPathsAndRelativeValuesForViewerOffset:











###Layout 
####wantsFullScreenLayout   deprecated in iOS 7

####Extended edges
	typedef NS_OPTIONS(NSUInteger, UIExtendedEdge) {

	


new behavior for the status bar

new status bar style 

	 typedef NS_ENUM(NSInteger, UIStatusBarStyle) {

### Custom Transitions
####     UIViewControllerTransitioningDelegate

	 @property (nonatomic,retain) id <UIViewControllerTransitioningDelegate>



####UIViewControllerAnimatedTransitioning


####UIViewControllerInteractiveTransitioning



###Bluetooth State Restoration

####Launch options keys




			 - application:openURL:sourceApplication:annotation: call








###UIDynamicBehavior




	
		 NSString *const UIContentSizeCategoryExtraSmall;
	 NSString *const UIContentSizeCategoryDidChangeNotification;


##Text Kit     

	 



