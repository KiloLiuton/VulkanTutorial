# VulkanTutorial
Vulkan tutorial followed at https://vulkan-tutorial.com/Introduction

This code renders the chalet model (https://sketchfab.com/models/e925320e1d5744d9ae661aeff61e7aef) from scratch by setting up a Vulkan application.

The steps involved are:
		createInstance();   ---------------fill info structs and call vkCreateInstance
		setupDebugCallback();   -----------fill VkDebugReportCallback struct and call
                                       vkGetInstanceProcAddr to setup debug through validation layers
		createSurface();   ----------------calls glfwCreateWindowSurface and create a window
		pickPhysicalDevice();   -----------seraches for a device with compatible swapchain format and
                                       swapchain presentMode and creates a physical device
		createLogicalDevice();   ----------finds out which queue families are supported by the picked physical
                                       device and if all required families are available
		createSwapChain();   --------------
		createImageViews();   -------------   
		createRenderPass();   -------------   
		createDescriptorSetLayout();   ----   
		createGraphicsPipeline();   -------   
		createCommanPool();   -------------   
		createDepthResources();   ---------   
		createFramebuffers();   -----------   
		createTextureImage();   -----------   
		createTextureImageView();   -------   
		createTextureSampler();   ---------   
		loadModel();   --------------------   
		createVertexBuffer();   -----------   
		createIndexBuffer();   ------------   
		createUniformBuffer();   ----------   
		createDescriptorPool();   ---------   
		createDescriptorSet();   ----------   
		createCommandBuffers();   ---------   
		createSemaphores();   -------------   
