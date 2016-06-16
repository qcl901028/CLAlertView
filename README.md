# CLAlertView


一个弹框只需要两行代码

 CLAlertView *alert = [[CLAlertView alloc] initWithAlertViewWithTitle:@"标题"  text:@"内容" DefauleBtn:@"确定" cancelBtn:@"取消" defaultBtnBlock:^(UIButton *defaultBtn) {
        
        [SVProgressHUD showWithStatus:@"正在加载。。。"];
        
        [self loadData];
        
    } cancelBtnBlock:^(UIButton *cancelBtn) {
        
    }];
    
    
    
    [alert show];
    
    
    
    
    
