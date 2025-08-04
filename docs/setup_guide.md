# Setup Guide: AI Research Agent

## Prerequisites
- Python 3.11 or higher
- IBM Cloud account with watsonx.ai Studio access
- Git installed on your system

## Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/ai-research-agent-ibm-granite.git
cd ai-research-agent-ibm-granite
```

## Step 2: Set Up IBM Cloud Credentials

### 2.1 Create IBM Cloud Account
1. Visit [IBM Cloud](https://cloud.ibm.com/)
2. Sign up for a free account
3. Navigate to watsonx.ai Studio

### 2.2 Get API Credentials
1. Go to IBM Cloud Console
2. Navigate to "Manage" > "Access (IAM)" > "API keys"
3. Create a new API key
4. Copy the API key for later use

### 2.3 Set Up watsonx.ai Studio Project
1. Access watsonx.ai Studio
2. Create a new project
3. Note down your project ID
4. Ensure IBM Granite model is available

## Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

## Step 4: Configure Environment Variables
Create a `.env` file in the project root:
```bash
# IBM Cloud Credentials
IBM_CLOUD_API_KEY=your_ibm_cloud_api_key_here
WATSONX_PROJECT_ID=your_project_id_here

# Optional: Additional configurations
ARXIV_MAX_RESULTS=10
LOG_LEVEL=INFO
```

## Step 5: Update Notebook Configuration
1. Open `notebooks/Research_Agent_Implementation.ipynb`
2. Update the following variables:
   ```python
   IBM_CLOUD_API_KEY = "YOUR_IBM_CLOUD_API_KEY_HERE"
   WATSONX_PROJECT_ID = "YOUR_PROJECT_ID_HERE"
   ```

## Step 6: Run the Research Agent
1. Start Jupyter notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to `notebooks/Research_Agent_Implementation.ipynb`
3. Run all cells to test the implementation

## Troubleshooting

### Common Issues

#### 1. API Key Authentication Error
**Problem**: "Invalid API key" error
**Solution**: 
- Verify your IBM Cloud API key is correct
- Ensure the API key has proper permissions
- Check if the key is expired

#### 2. watsonx.ai Studio Access
**Problem**: Cannot access watsonx.ai Studio
**Solution**:
- Verify your IBM Cloud account is active
- Check if you have watsonx.ai Studio access
- Contact IBM Cloud support if needed

#### 3. Dependencies Installation
**Problem**: Package installation fails
**Solution**:
- Update pip: `pip install --upgrade pip`
- Use virtual environment: `python -m venv venv`
- Install packages in virtual environment

#### 4. arXiv API Issues
**Problem**: Cannot fetch papers from arXiv
**Solution**:
- Check internet connection
- Verify arXiv service status
- Reduce request frequency if rate limited

### Performance Optimization
- Use virtual environment for isolation
- Monitor API usage limits
- Cache results when possible
- Use appropriate timeout values

## Security Best Practices
1. **Never commit API keys** to version control
2. Use environment variables for sensitive data
3. Regularly rotate API keys
4. Monitor API usage and costs
5. Follow IBM Cloud security guidelines

## Next Steps
1. Explore the notebook implementation
2. Customize the research queries
3. Add your own analysis functions
4. Integrate with additional data sources
5. Deploy to production environment

## Support Resources
- [IBM Cloud Documentation](https://cloud.ibm.com/docs)
- [watsonx.ai Studio Guide](https://dataplatform.cloud.ibm.com/docs)
- [arXiv API Documentation](https://arxiv.org/help/api)
- [Project Issues](https://github.com/yourusername/ai-research-agent-ibm-granite/issues) 