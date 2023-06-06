KeyError: 'close_date'
Traceback:
File "c:\programdata\anaconda3\lib\site-packages\streamlit\script_runner.py", line 354, in _run_script
    exec(code, module.__dict__)
File "C:\Users\wevans\Downloads\AutoGPT\SMOL\developer\generated\dashboard.py", line 83, in <module>
    main()
File "C:\Users\wevans\Downloads\AutoGPT\SMOL\developer\generated\dashboard.py", line 73, in main
    preprocessed_data = preprocess_data(raw_data)
File "C:\Users\wevans\Downloads\AutoGPT\SMOL\developer\generated\data_processing.py", line 8, in preprocess_data
    data["date"] = pd.to_datetime(data["close_date"])
File "c:\programdata\anaconda3\lib\site-packages\pandas\core\frame.py", line 3458, in __getitem__
    indexer = self.columns.get_loc(key)
File "c:\programdata\anaconda3\lib\site-packages\pandas\core\indexes\base.py", line 3363, in get_loc
    raise KeyError(key) from err