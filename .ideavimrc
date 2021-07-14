""""""""""""""""""""""""""""""""""""""Configuration""""""""""""""""""""""""""""""""""""""
set showmatch
set hlsearch
set incsearch
set ignorecase
set smartcase
set history=3000000
set commentary
:set vb
:set keep-english-in-normal

""""""""""""""""""""""""""""""""""""""Basics""""""""""""""""""""""""""""""""""""""
"debug Artifact
nmap <C-j> :action StepOver<CR>
nmap <C-k> :action Resume<CR>
nmap <C-h> :action StepOut<CR>
nmap <C-l> :action ForceStepInto<CR>
"Mobile specialization
vmap <C-j> <C-e>
vmap <C-k> <C-y>
vmap <C-h> 10zh
vmap <C-l> 10zl
imap <C-j> <Down>
imap <C-k> <Up>
imap <C-h> <Left>
imap <C-l> <Right>
imap <C-i> <CR>
"Left and right vision
nnoremap zH 50zh
nnoremap zL 50zl
"^$ The symbol is too hard to press
map gh ^
map gl $
""""""""""""""""""""""""""""""""""""""Refactoring""""""""""""""""""""""""""""""""""""""
noremap <Space>re :action RenameElement<CR>
noremap <Space>mv :action Move<CR>
noremap <Space>ms :action MakeStatic<CR>
noremap <Space>ci :action ConvertToInstanceMethod<CR>
noremap <Space>il :action Inline<CR>
noremap <Space>em :action ExtractMethod<CR>
noremap <Space>ei :action ExtractInterface<CR>
noremap <Space>ef :action EncapsulateFields<CR>
noremap <Space>rmo :action ReplaceMethodWithMethodObject<CR>
noremap <Space>iv :action IntroduceVariable<CR>
noremap <Space>ic :action IntroduceConstant<CR>
noremap <Space>ip :action IntroduceParameter<CR>
noremap <Space>if :action IntroduceField<CR>
noremap <Space>po :action IntroduceParameterObject<CR>
noremap <Space>pd :action MemberPushDown<CR>
noremap <Space>pu :action MembersPullUp<CR>
noremap <Space>RF :action RenameFile<CR>
noremap <Space>cs  :action ChangeSignature<CR>
noremap <Space>ai :action AnonymousToInner<CR>
""""""""""""""""""""""""""""""""""""""Jump articles""""""""""""""""""""""""""""""""""""""
noremap <Space>te :action SearchEverywhere<CR>
nnoremap <Space>ts mm`m:action GotoSymbol<CR>
noremap  <Space>tu  mm`m:action Toolkit.GotoService<CR>
nnoremap <Space>ta mm`m:action GotoAction<CR>
noremap <Space>tf mm`m:action GotoFile<CR>
noremap <Space>tt mm`m:action GotoTest<CR>
noremap <Space>tc mm`m:action GotoClass<CR>
noremap <Space>tp mm`m:action FindInPath<CR>
noremap <Space>ne mm`m:action GotoNextError<CR>
noremap <Space>pe mm`m:action GotoPreviousError<CR>
noremap <Space>gs mm`m:action GotoSuperMethod<CR>
noremap <Space>gi mm`m:action GotoImplementation<CR>
noremap <Space>g, mm`m:action JumpToLastChange<CR>
noremap <Space>g; mm`m:action JumpToNextChange<CR>
noremap <Space>rf :action RecentFiles<CR>
noremap <Space>rF :action RecentChangedFiles<CR>
noremap <Space>nw :action NextProjectWindow<CR>
noremap <Space>pw :action PreviousProjectWindow<CR>
""""""""""""""""""""""""""""""""""""""SQL""""""""""""""""""""""""""""""""""""""
noremap <Space>sc :action Console.Transaction.Commit<CR>
noremap <Space>sr :action Console.Transaction.Rollback<CR>
noremap <Space>se :action Console.Jdbc.Execute<CR>
"Open the database log window, provided the MyBatis Log Plugin is installed
noremap <Space>AL :action TailMyBatisLog0<CR>:action ActivateMyBatisLogToolWindow<CR>
""""""""""""""""""""""""""""""""""""""Run""""""""""""""""""""""""""""""""""""""
nnoremap <Space>rc :action RunConfiguration<CR>
noremap <Space>rr :action Run<CR>
noremap <Space>rn :action RunClass<CR>
noremap <Space>dd :action Debug<CR>
noremap <Space>dn :action DebugClass<CR>
noremap <Space>cc :action Coverage<CR>
noremap <Space>cn :action RunCoverage<CR>
noremap <Space>sp   :action Stop<CR>
""""""""""""""""""""""""""""""""""""""Debug""""""""""""""""""""""""""""""""""""""
noremap <Space>bp :action ToggleLineBreakpoint<CR>
noremap <Space>qe :action QuickEvaluateExpression <CR>
noremap <Space>ee :action EvaluateExpression <CR>
noremap <Space>fr :action Debugger.ForceEarlyReturn<CR>
noremap <Space>daw :action Debugger.AddToWatch<CR>
noremap <Space>fc :action ForceRunToCursor<CR>
noremap <Space>hs :action Hotswap<CR>
noremap <Space>DD :action JRebel Debug<CR>
noremap <Space>rab :action Debugger.RemoveAllBreakpointsInFile<CR>
noremap <Space>raB :action Debugger.RemoveAllBreakpoints<CR>
noremap <Space>df :action Debugger.PopFrame<CR>
noremap <Space>pp :action ShowExecutionPoint<CR>
noremap <Space>ds :action StreamTracerAction<CR>
noremap <Space>mb :action XDebugger.MuteBreakpoints<CR>


""""""""""""""""""""""""""""""""""""""Window""""""""""""""""""""""""""""""""""""""
noremap <Space>AM  :action ActivateMavenToolWindow<CR>
noremap <Space>AD  :action ActivateDatabaseToolWindow<CR>
noremap <Space>AT   :action ActivateTODOToolWindow<CR>
noremap <Space>AF :action ActivateFavoritesToolWindow<CR>
noremap <Space>AP :action ActivateProjectToolWindow<CR>
noremap <Space>AG :action ActivateVersionControlToolWindow<CR>
noremap <Space>AS :action ActivateServicesToolWindow<CR>
noremap <Space>AB :action ViewBreakpoints<CR>
noremap <Space>AR :action ActivateRestServicesToolWindow<CR>
nnoremap <Space>wd :action ActivateDebugToolWindow<CR>
nnoremap <Space>wr :action ActivateRunToolWindow<CR>
nnoremap <Space>wh :action HideActiveWindow<CR>
nnoremap <Space>mm :action MaximizeToolWindow<CR>
noremap <Space>ha :action HideAllWindows<CR>
noremap <Space><Space> :action HideAllWindows<CR>
noremap <Space>si :action SelectInProjectView<CR>
noremap <Space>eb :action EditBreakpoint<CR>

""""""""""""""""""""""""""""""""""""""Information""""""""""""""""""""""""""""""""""""""
noremap <Space>ed :action ShowErrorDescription<CR>
noremap <Space>ti :action ExpressionTypeInfo<CR>
noremap <Space>pi :action ParameterInfo<CR>
noremap <Space>jd :action QuickJavaDoc<CR>
noremap <Space>fs mm`m:action FileStructurePopup<CR>
noremap <Space>sd  :action ShowUmlDiagram<CR>
noremap <Space>ch :action CallHierarchy<CR>
nnoremap <Space>fu :action FindUsages<CR>
nnoremap <Space>su :action ShowUsages<CR>
noremap <Space>mh :action MethodHierarchy<CR>
noremap <Space>ss  :action ShowSettings<CR>
noremap <Space>ps :action ShowProjectStructureSettings<CR>
""""""""""""""""""""""""""""""""""""""Project""""""""""""""""""""""""""""""""""""""
noremap <Space>cP :action CloseProject<CR>
noremap <Space>CP :action CloseProject<CR>
noremap <Space>oP :action OpenFile<CR>
noremap <Space>OP :action OpenFile<CR>
noremap <Space>nP :action NewProject<CR>
noremap <Space>NP :action NewProject<CR>
""""""""""""""""""""""""""""""""""""""Utilities""""""""""""""""""""""""""""""""
noremap <Space>sw :action SurroundWith<CR>
noremap <Space>= :action ReformatCode<CR>
noremap <Space>sm :action ShowPopupMenu<CR>
noremap <Space>st :action SaveAsTemplate<CR>
noremap <Space>cap   :action CopyAbsolutePath<CR>
noremap <Space>ccp   :action CopyContentRootPath<CR>
noremap <Space>oi :action OptimizeImports<CR>
nnoremap <Space>cv :action ChangeView<CR>
noremap <Space>co :action CloseAllEditorsButActive<CR>
noremap <Space>ag :action antlr.Generate<CR>:action antlr.Generate<CR>
noremap <Space>bc   :action ByteCodeViewer<CR>
noremap <Space>qq   :action $TranslateTextComponent<CR>
noremap <Space>tr :action $TranslateAndReplaceAction<CR>
noremap <Space>gfu :action GenerateFullRestUrl<CR>
noremap <Space>atf :action AddToFavorites<CR>
noremap <Space>cE :action CopyElement<CR>
noremap <Space>nE :action NewElement<CR>
noremap <Space>dE :action SafeDelete<CR>
nnoremap <Space>cp :action CheckinProject<CR>
nnoremap <CR><CR> :action ShowIntentionActions<CR>
nnoremap <Space><CR> :action GotoNextError<CR>
noremap <Space>nc :action NewClass<CR>
noremap <Space>ps :action ShowProjectStructureSettings<CR>
noremap <Space>ri :action RevealIn<CR>
noremap <Space>ga :action Generate<CR>
noremap <Space>cu :action CloseAllUnmodifiedEditors<CR>
noremap <Space>oc :action OpenCodotaSearch<CR>
noremap <Space>AC :action ActivateCodotaToolWindow<CR>
"Codota activation window, Codota plug-in needs to be installed in advance
noremap <Space>cl :action CodotaLeanSearchCrossRefAction<CR>


